Solution to Exercises for toy app
ans1:
browser makes request to the url /users/1/edit
Rails routes it to edit in the users controller
calls the view 
view uses embeded ruby to render HTML
controller passes the HTML back to the browser


ans3: edit.html.erb

## Validations
validations are easy . In models you need to use a field **validates**
```
validates: the field of the model where you want to use validation, {what type of validation( eg: length):{(eg-max/min): amout you need }}
```
### Note ###
By using rails library called active record it arranges all the users in the database
Active record is the interface that is given by rails for interaction with the database. It lets you structure your data models for your users, blog posts, comments, followers, etc.

## Inheritance ##
modals inherit from applicationRecord which inturn inherits from activeRecord(Base).

controllers inherit from applicationContoller which inherits from actionController(Base).