# How to use Assertions in JMeter (Response Example)
## What is an Assertion?

Assertions help verify that your server under test returns the expected results.

## Types of Assertions

Following are some commonly used Assertions in JMeter:

- Response Assertion
- Duration Assertion
- Size Assertion
- XML Assertion
- HTML Assertion

## Steps to use Response Assertion

### Response Assertion

![Response Assertion](AssertionImages/image.png)

The response assertion lets you add pattern strings to be compared against various fields of the server response.

For example, you send a user request to the website [http://www.google.com](http://www.google.com) and get the server response. You can use Response Assertion to verify if the server response contains the expected pattern string (e.g. “OK”).

### Duration Assertion

The Duration Assertion tests that each server response was received within a **given amount** of time. Any response that takes longer than the given number of milliseconds (specified by the user) is marked as a failed response.

For example, a user request is sent to [www.google.com](http://www.google.com) by JMeter and gets a response within the expected time of 5 ms, then the test case passes; else, the test case fails.

![Duration Assertion](AssertionImages/image2.png)

### Size Assertion

The Size Assertion tests that each server response contains the expected number of bytes. You can specify that the size be equal to, greater than, less than, or not equal to a given number of bytes.

JMeter sends a user request to [www.google.com](http://www.google.com) and gets a response packet with a size less than the expected 5000 bytes, then the test case passes; else, the test case fails.

## Size Assertion

The Size Assertion tests that each server response contains the expected number of byte in it. You can specify that the size be equal to, greater than, less than, or not equal to a given number of bytes.

JMeter sends a user request to [www.google.com](http://www.google.com) and gets response packet with size less than expected byte 5000 bytes a test case pass. If else, test case failed.

## XML Assertion

The XML Assertion tests that the response data consists of a formally correct XML document.

![XML Assertion](AssertionImages/image3.png)

## HTML Assertion

The HTML Assertion allows the user to check the HTML syntax of the response data. It means the response data must be met the HTML syntax.

![HTML Assertion](AssertionImages/image4.png)
