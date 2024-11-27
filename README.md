# Visualize-a-Relational-Database
The goal of this project is to set up our own relational database and visualize it using some fun charts... all using AWS.. 

Once I was comfortable with QuickSight, I decided to go deeper. Instead of working with a static dataset, I wanted to visualize live data from a relational database. For that, I turned to Amazon RDS.

I created a MySQL database in RDS. The setup process was surprisingly flexible. You can adjust everything — storage, instance type, networking. It felt like AWS wanted me to customize the database for exactly what I needed. Once the database was up, I configured access using VPC, IAM roles, and security groups. This part took more thought. RDS is powerful, but it’s not open by default — you have to tell it who can access what.

With the database secure, I moved on to populating it. I used SQL scripts to load sample data. It reminded me how structured relational data is compared to what I’d work with later in DynamoDB. Once the data was in place, I connected the database to QuickSight. The charts and tables I built gave me a new perspective on relational databases — and how to make their data useful.
