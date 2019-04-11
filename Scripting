
# your Gmail account  
import smtplib 
  
# creates SMTP session 
s = smtplib.SMTP('smtp.gmail.com', 587) 
  
# start TLS for security 
s.starttls() 
  
# Authentication 
s.login("ayushig4072@gmail.com", "Password") 
  
# message to be sent 
message = "This is Ayushi"
  
# sending the mail 
s.sendmail("ayushig4072@gmail.com", "ayushig4072@gmail.com", message) 
  
# terminating the session 
s.quit() 
