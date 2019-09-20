# StringTest
## Test -> StringTest
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of String. 
* The official document of this knowledge point is https://www.tutorialspoint.com/java/lang/java_lang_string.htm.
* Q2: Why the test failed at first?
* The test failed at first because the expected  result and the actual result are not the same.
* Q3: Why you corrected the test that way?
* I corrected it this way since there was a manipulation of the value of the string, where "original" is replaced with "new".
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> all_modification_method_will_create_new_string
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of String. 
* The official document of this knowledge point is https://www.tutorialspoint.com/java/lang/java_lang_string.htm.
* Q2: Why the test failed at first?
* The test failed at first because the expected  result and the actual result are not the same.
* Q3: Why you corrected the test that way?
* I corrected it this way since there was a manipulation of the value of the string. The spaces where removed and thus the original string with spaces are not equal to the modified string.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> will_create_new_string_when_concat
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of String, particularly concat. 
* The official document of this knowledge point is https://www.tutorialspoint.com/java/lang/java_lang_string.htm.
* Q2: Why the test failed at first?
* The test failed at first because the expected  result and the actual result are not the same due to the modified string.
* Q3: Why you corrected the test that way?
* I corrected it this way since there was a manipulation of the value of the string. The original string was modified by adding new words. So when comparing it to the original, it is no longer equal.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> should_taken_string_apart
## Test -> should_taken_string_apart_continued
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of String, substring particularly. 
* The official document of this knowledge point is https://www.tutorialspoint.com/java/lang/java_lang_string.htm.
* Q2: Why the test failed at first?
* The test failed at first because the expected  result and the actual result are not the same due to the modified string.
* Q3: Why you corrected the test that way?
* I corrected it this way since there was a manipulation of the value of the string. The original string was modified by removing characters depending on the range. So when comparing it to the original, it is no longer equal.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> should_break_string_into_words
## Test -> should_break_string_into_words_customized
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of String, split in particular. 
* The official document of this knowledge point is https://www.tutorialspoint.com/java/lang/string_split_limit.htm.
* Q2: Why the test failed at first?
* The test failed at first because the expected  result and the actual result are not the same due to the modified string.
* Q3: Why you corrected the test that way?
* I corrected it this way since there was a manipulation of the value of the string. The original string was modified by separating them depending on the marker that is indicated. So when comparing it to the original, it is no longer equal.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> should_create_ascii_art
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of String, StringBuilder in particular. 
* The official document of this knowledge point is https://www.tutorialspoint.com/java/lang/java_lang_stringbuilder.htm.
* Q2: Why the test failed at first?
* The test failed at first because the expected  result and the actual result are not the same due to the modified string. The builder was not assigned with any value.
* Q3: Why you corrected the test that way?
* I corrected it this way since there was no string inside the builder. Using Append will add the expected characters to get the same result.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> should_calculate_checksum_of_a_string
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of String, toCharArray in particular. 
* The official document of this knowledge point is https://www.tutorialspoint.com/java/lang/string_tochararray.htm.
* Q2: Why the test failed at first?
* The test failed at first because the expected  result and the actual result are not the same due to the modified string. Sum was not assigned in a computation to add all the characters.
* Q3: Why you corrected the test that way?
* I corrected it this way since there it would be cleaner to use for loop. To get all the characters without assigning each one to a variable.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> should_convert_unicode_escape
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of String, Ascii and unicodes in particular. 
* The official document of this knowledge point is https://hajsoftutorial.com/java-ascii-unicode/.
* Q2: Why the test failed at first?
* The test failed at first because the expected  result and the actual result are not the same.
* Q3: Why you corrected the test that way?
* I corrected it this way since there the codes were already given, all that is needed is to connect each one.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> should_reverse_a_string
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of String, StringBuilder with its function reverse() in particular. 
* The official document of this knowledge point is https://www.tutorialspoint.com/java/lang/stringbuilder_reverse.htm.
* Q2: Why the test failed at first?
* The test failed at first because the expected  result and the actual result are not the same.
* Q3: Why you corrected the test that way?
* I corrected it this way since in the document I have read there is also a function for reversing strings.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> should_compare_string_with_different_cases
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of String. 
* The official document of this knowledge point is https://www.tutorialspoint.com/java/lang/java_lang_string.htm.
* Q2: Why the test failed at first?
* The test failed at first because the expected  result and the actual result are not the same. The first boolean compared the 2 string with case sensitivity, while the second boolean compared the 2 ignoring if it is uppercase or not.
* Q3: Why you corrected the test that way?
* I corrected it this way since in the document I have read there is also a function for comparing strings whether it is case sensitive or not.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> should_format_string
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of String format. 
* The official document of this knowledge point is https://www.tutorialspoint.com/java/lang/string_format_locale.htm.
* Q2: Why the test failed at first?
* The test failed at first because the expected  result and the actual result are not the same. The variables are not yet placed in the right position.
* Q3: Why you corrected the test that way?
* I corrected it this way since with the given conversion chars list, it gave me a hint that the "%d" and "%s" are the positions of the variables.
* Q4: Do you have further questions on this knowledge point?
* No.