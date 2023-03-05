## Problem Statement: Calculate overall percentage obtained by cadet in different assessments

**This program should collect assessment details for cadet and calculate percentage score obtained by cadet for all the assessments. The assessments are of different type and have different maximum scores**

**This exercise contains a class named Program with the below given methods.**

     +GetOverAllScore() : int
         - Should take set of Assessment Cards as parameter
         - Retrieve the maximum score for each assessment type. Assessment type should be an enumeration
         - Should return percentage score value as integer for the average calculated

------------------------------------------------------

      +GenerateScoreCard() : string
         - Should take set of assessment cards as parameter
         - Should also take cadet no, cadet name, overall percentage score calculated.
         - Retrieve the maximum score for each assessment type.
         - Should build a string using StringBuiler that outputs cadetno, cadetName, date of appraisal, appraisal type, card data and overall score

------------------------------------------------------

The program should also contain definitions for  enumerated and structure types as suggested below:

      +AssessmentType : enum
         - Should contain named constants for types of assessment such as Quiz, Calibration, KBA and Hackathon
         - Maximum scores for these assessment types are :
            - Quiz : 50
            - KBA : 100
            - Calibration : 150
            - Hackathon : 200
         - The maximum score must be obtained from the enum values itself

-------------------------------------------------------

      + AssessmentCard : struct
         - Should declare struct with score, assessment type and assessment date
         - Should declare assessment type of type enum AssessmentType
         - Should be used as type for storing multiple card details

--------------------------------------------------------

## Instructions

- Avoid printing unnecessary values
- Take care of whitespace/trailing whitespace
- Do not change the provided class/method names unless instructed
- Follow best practices while coding
- Regularly push code to git
