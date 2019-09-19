# should_perform_logical_boolean_operations()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: Creating a customize exception with message. https://www.baeldung.com/java-new-custom-exception
##### 2. Why the test failed at first?
    Answer: StringFormatException is throwing an not expected exception.
##### 3. Why you corrected the test that way?
    Answer: Because as per the documentation that I read, that's the good way to set an exception.
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# should_customize_exception_continued()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: reating a customize exception with message and cause. https://www.baeldung.com/java-new-custom-exception
##### 2. Why the test failed at first?
    Answer: StringFormatException is throwing an not expected exception.
##### 3. Why you corrected the test that way?
    Answer: Because as per the documentation that I read, that's the good way to set an exception.
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# should_be_careful_of_the_order_of_finally_block()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: Finally will always run in try()catch(). http://tutorials.jenkov.com/java-exception-handling/basic-try-catch-finally.html
##### 2. Why the test failed at first?
    Answer: Requirements on Assert not met
##### 3. Why you corrected the test that way?
    Answer: Because that should be the expected value of expectedResult
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# should_use_the_try_pattern()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: the knowledge point of this test is the try(). https://docs.oracle.com/javase/tutorial/essential/exceptions/tryResourceClose.html
##### 2. Why the test failed at first?
    Answer: Because expected value is not equal to the actual value
##### 3. Why you corrected the test that way?
    Answer: Because that should be the right value
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# should_call_closing_even_if_exception_throws()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: AutoCloseable is the knowledge Point of the test. https://docs.oracle.com/javase/tutorial/essential/exceptions/tryResourceClose.html
##### 2. Why the test failed at first?
    Answer: Because expected value is not equal to the actual value
##### 3. Why you corrected the test that way?
    Answer: Because that should be the right value with AutoClosable 
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# should_get_method_name_in_stack_frame()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: returning a default value in getCurrentMethodName. 
##### 2. Why the test failed at first?
    Answer: Unmatched expected and actual value
##### 3. Why you corrected the test that way?
    Answer: Because there is no such method name com.cultivation.javaBasic.ExceptionTest.should_get_method_name_in_stack_frame, that's why I put it as is as the actual.
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
