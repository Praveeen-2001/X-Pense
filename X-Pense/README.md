# X-Pense : A Personalised Expense Tracker #





The objective of this project was to provide a user- friendly application, that could make the process of managing one’s expenses in an easier and effective manner by providing insightful charts that will help the user to derive useful data from it and understand where his finances are being consumed, which could in turn help him to manage his expenditures in a more coherent manner.This app has been successfully deployed on the TANZU APPLICATION SERVICE.
This project showcases the implementation of an expense tracker which was made using Python FLASK, POSTGRES and the fundamental web development technologies like HTML, CSS & JS.
This app provides the end users the following features:



- Would allow users to set a budget for a particular month & year following which 
- The user would then would be able to add any expenditures to that particular month & year that was set.
- Supports additions of multiple budget limits for various months along with the functionality of navigating between all the budgets created and the expenses created for theat specified budget month/year.
- Warning for when 75% of the budget has been consumed.
- E-Mail alerts for when the user’s expenditures were to cross the budget limit set for that month.
- Functionality to download/e-mail a report of the expenditures for the budget month that was set.
- Provides the user the ability to visualize his expenditures in a graphical form.

![image](https://user-images.githubusercontent.com/73709251/117812845-efe0a600-b27f-11eb-919f-a041cd519a90.png)

Project Report : <https://drive.google.com/file/d/1xaqs3_mScAYdkXRmX1f3zjNREYJDPYeW/view?usp=sharing>

Click on the link to access the product : <https://x-pense-final.herokuapp.com/>


> ### Replication & Usage

- Close the repository first:
```git clone https://github.com/xosteve26/X-Pense.git ```

- Upon cloning, run the `pip install -r requirements.txt` command in the directory where you've cloned the repository in order to install the required dependencies.

- Create a `.env` file and craete a varaible named `SENDGRID_API_KEY` EX: ```SENDGRID_API_KEY="You Sendgrid API Key" ``` and store the sendgrid api key in order to make use of the email funcitonality.

- Create the following varibles `db_username`,`db_password`,`db_host`,`db_port` with your database's credentials as values in the `.env` file .

