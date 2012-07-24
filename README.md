#  devise-i18n-views

I18n support and translations to **[Devise v2.+](https://github.com/plataformatec/devise)** views.

## Translation file stub 

``` yml
en:
  devise:
    mailer:
      confirmation_instructions:
        subject: 'Confirmation instructions'
          greeting: 'Welcome %{recepient}!'
          instruction: 'You can confirm your account email through the link below:'
          action: 'Confirm my account'
      reset_password_instructions:
        subject: 'Reset password instructions'
          greeting: 'Hello %{recepient}!'
          instruction: 'Someone has requested a link to change your password, and you can do this through the link below.'
          action: 'Change my password'
          instruction_2: "If you didn't request this, please ignore this email."
          instruction_3: "Your password won't change until you access the link above and create a new one."
      unlock_instructions:
        subject: 'Unlock Instructions'
          greeting: 'Hello %{recepient}!'
          message: 'Your account has been locked due to an excessive amount of unsuccessful sign in attempts.'
          instruction: 'Click the link below to unlock your account:'

``` 	  	

## Submit or edit a translation for devise-i18n-views
 
* Fork the latest master
* Create a translation file or edit an existing one under `locales`
* Make a pull request

## Copyright

Copyright (c) 2012 mcasimir. See LICENSE.txt for
further details.

