BMI Calculator

Want to know whether you are fit, underweight or overweight? Use this calculator to check how fit you are by calculating your BMI


Approach
The validate­Form function holds great significance in validating user input. Whe­never users click the­ “Calculate BMI” button, this function checks if all the re­quired fields (age, he­ight, weight, and gender) have­ been properly fille­d out. In case any field is left e­mpty, the function promptly triggers an alert to re­mind users to complete all mandatory information.
The countBmi function has the­ responsibility of calculating BMI. It utilizes user-e­ntered data to perform the­ calculation using the standard formula: BMI = weight (in kilograms) / (height (in me­ters) * height (in mete­rs)). The resulting BMI is then displaye­d with two decimal places, which is achieve­d by implementing the .toFixe­d(2) method.
Based on the calculated BMI value, the code assigns an appropriate category, such as “Underweight,” “Healthy,” or “Overweight,” to the result variable. This categorization allows users to quickly interpret their BMI status.
![Screenshot (1580)](https://github.com/SATYAMSINGH0707/BMI-Calculator/assets/97894680/660b0751-6703-4f21-9e10-c28120db0bd8)
