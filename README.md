# My-Marvel

## A place for Marvel Fans to Create Read Update and Delete Marvel Movies

### Goal of this app is to have users create a shareable list of the MCU movies.
### They should be able to title, save, delete and share their lists.

User Stories
When I click Sign up, I should go to signup page.<br/>
When I click Log in, I should be able to log in and view My List page.<br/>
When I click Community List, I should see other users lists/viewing orders.<br/>
Should be able to save other users lists.<br/>
Delete Lists and Edit Lists.<br/>
    
    
MVP CHECKLIST:<br/>
User Sign up<br/>
User Log in<br/>
Create<br/>
Delete and Edit<br/>
Shared Community list page<br/>


STRETCH GOALS:<br/>
Saving Community Lists<br/>
Search and Filtering lists<br/>
Super Cool Styling<br/>
Sound Effects<br/>

Routes:<br/>

app.post(‘users/‘, userController.signup)<br/>

app.post(‘users/login’, userController.login)<br/>

app.get(‘users/verify’, userController.verify)<br/>

app.get(‘lists/‘, listController.findAll)<br/>

app.post(‘lists/‘, listController.create)<br/>

app.post(‘lists/edit’, listController.update)<br/>

app.delete(‘lists/:id’, listController.destroy)

##ERB
![image](https://user-images.githubusercontent.com/79672776/116503577-7494f280-a884-11eb-9c88-0864fbff7b67.png)

##WIREFRAMES
![image](https://user-images.githubusercontent.com/79672776/116503626-8ffffd80-a884-11eb-9d08-41dbae67b13c.png)
![image](https://user-images.githubusercontent.com/79672776/116503637-95f5de80-a884-11eb-95ec-6551ed4938ce.png)
![image](https://user-images.githubusercontent.com/79672776/116503655-9b532900-a884-11eb-84a2-2c52e260f505.png)
![image](https://user-images.githubusercontent.com/79672776/116503665-a443fa80-a884-11eb-81f5-eb63d3dd8abc.png)
![image](https://user-images.githubusercontent.com/79672776/116503670-aa39db80-a884-11eb-8f00-470dc7e0c068.png)
![image](https://user-images.githubusercontent.com/79672776/116503672-ae65f900-a884-11eb-94d8-bb8594cdb8e1.png)
