# This is a basic Register, Login, Forgot and Reset Password Project using MERN Stack.

## [Click Here](https://forgot-password-fullstack-sandeep.netlify.app/) to view the deployed site.


Design a forget password page, where the user enters his e-mail id.

Check if the user exists in the DB.

If the user is not present send an error message.

If the user is found generate a random string and send a link with that random string in
the mail

Store the random string in DB for later verification.

When the user enters that link, retrieve the random string and pass it to DB.

Check if the random string matches.

If the string matches show the password reset form.

Store the new password and clear the random string in the DB once the user submits
the form.

If the string does not match send an error message.

The flow image is given below.
