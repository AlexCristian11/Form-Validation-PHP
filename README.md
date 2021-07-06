# Form Validation PHP

I have created a form for a user to create a profile on the website. I collected the user's **name**, **character**, **email** and **birth year**. 

## Validation

- Name must not exist in "existing_users" array
- Character must be either one from the array "[wizard, mage, orc]"
- Email is validated using **filter_var()** function
- Birth year is validated using **filter_var()** function and **options** to be in range from 1900 until current year

If everything is validated correctly , every variable will appear in the preview area. Otherwise , a **validation_error** string will appear describing the issue.
