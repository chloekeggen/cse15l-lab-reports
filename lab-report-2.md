Hello, thank you for checking out my lab report 2!

Today, we will be showing you my String Server and a few lessons about bugs and symptoms!

# Part 1: Writing a web server

## Below is the code for my String Server: 

![Image](CodeServer1.PNG)

  -  This is the code that tells our server what we want to happen. If the path of my url is "add-message", it will add the string I write in the next line. 

![Image](CodeServer2.PNG)

  - This is the code that sets up the port for our server so you can access it on the web browser. 

## Below is my code in action on a web browser!

![Image](ServerPrint.PNG)

- The handleRequest method takes in my url as a parameter. If the url contains "```/add-message```" as its path, it finds the query and splits it at the "=" sign. It holds these values in a variable called "parameters". If the first part of the parameters equals to "s" (which stands for string), it will concatenate our inputted string to the variable ```string```.
  - The main method creates the server itself, so when running the terminal, it requires a port number. If no port number is given, it will throw an exception. Here, our port number is ```3902``` as you can see in our url.
- The relevant arguments to the handleRequest method is a valid url that contains "```/add-message```" as its path, and contains a query ```?s=```. The url also must contain a port number between ```1024 to 49151```. 
- Any inputted values, whether an int, double, or a character will be changed into a String. An example of this is below:

![Image](ServerPrints.PNG)

- Like the first screenshot, the handleRequest method takes in the url, and since the url contains the necessary path and query, the variable parameters will hold whatever the input is in the url. In this example, I tried inputting numbers and characters, and these values will be held and concatenated on.
  - The main method, again, is called, and it needs a valid port number in order to create the server. 
- The relevant arguments are the url with the required path and query, and if these are not given correctly, the code returns a ```404 Not Found!``` error to let the user know. 
- Here, we can see clearly that the integers will be concatenated to the server as Strings, especially clear when we try adding two numbers together. ```4+5``` remainds ```4+5``` instead of becoming ```9``` because it is converted into a String!

# Part 2: Bugs

## 1. Failure-inducing input
```
@Test
  public void testReversedLonger() {
    int[] input1 = {3, 4, 5};
    assertArrayEquals(new int[]{5, 4, 3 }, ArrayExamples.reversed(input1));
  }
 ```

## 2. Input that doesn't induce failure
```
  @Test
  public void testReversed() {
    int[] input1 = { };
    assertArrayEquals(new int[]{ }, ArrayExamples.reversed(input1));
  }
```
## 3. Symptom: Output of running the tests
 - The output when we try inputting the ```{3, 4, 5}```
![Image](BugReport.PNG)
 - The output when we try inputting the ```{ } ```
![Image](WorkingTest1.PNG)

## 4. The fix

Before: 
```
 static int[] reversed(int[] arr) {
    int[] newArray = new int[arr.length];
    for(int i = 0; i < arr.length; i += 1) {
      arr[i] = newArray[arr.length - i - 1];
    }
    return arr;
  }
```

After: 
```
 static int[] reversed(int[] arr) {
    int[] newArray = new int[arr.length];
    for(int i = 0; i < arr.length; i += 1) {
      newArray[i] = arr[arr.length - i - 1];
    }
    arr = newArray;
    return arr;
  }
 ```
What did we change? In our code before, we created a newArray with the length of our current array. With our for loop, all we were doing was emptying out our current array by basically copying over our empty array into it. So, for example, if we start at the beginning and our array length is 5: ```arr[0] = newArray[4]```, but our newArray is empty, so this just erases our array! 

In order to fix this, we copy the contents of our array into the newArray but backwards, so ```newArray[0] = arr[4]``` and onwards, ```newArray[1] = arr[3]``` until the entire list is reversed. It then makes our array equal the new array again, and returns it! 

# Part 3: What I learned!

  I have learned a great deal in the past two weeks. Something I found especially interesting was how easy it is to create a local server. I have had some practice in using localhost servers, but it all seemed more complicated somehow when I was doing it back then. I now have the code to easily create a server with a specific port number. Also, I have enjoyed learning the various definitions of bugs and symptoms, and the difference in definitions between the student and professional ideals of a working program. 
