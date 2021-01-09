*   Several methods added in the Patient class to improve functionality of the class.
    *   Class method update_name() added. It updates the name of the patient on record.
    *   Class method update_age() added. It updates the age of the patient on record.
    *   Class method update_bmi() added. It updates the BMI of the patient on record.
    *   Class method update_num_of_children() added. It updates the number of children of the patient on record.
    *   Class method update_smoking_status() added. It updates whether the patient is a smoker or not on record.
    *   Class method patient_profile(). It generates a dictionary that contains the patient's records.
*   The Patient class strings have been updated from using the str.format() method to using formatted string literals (f strings) inline with PEP 498.
*   Corrected typo in the .analyse_bmi() method.
*   Addition of ChangeLog.md to track changes while working on the code and ensure all changes are highlighted when new versions are commited.
*   Addition of Planned_Improvements.md to keep track of future improvements / considerations.