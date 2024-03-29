
# Azure SQL Database Setup
![image_2024-03-29_112428155](https://github.com/Malik-444/Azure-SQL/assets/151242422/6361316d-d18f-461e-856e-110feb445f3b)


**Project Description**:

Title: Setting Up a Scalable SQL Database in Azure

Description:
This project aims to demonstrate the implementation of a scalable SQL database in Microsoft Azure for a fictional e-commerce platform. The project involves creating a cloud-based database system to store product information, manage customer data, and process orders efficiently. By setting up this Azure SQL Database, the project showcases the use of cloud computing technology for robust data management, security, and scalability.

Key Components:
1. **Database Setup**: Creation of tables for products, customers, orders, and relationships between them.
2. **SQL Queries**: Writing SQL queries to retrieve, insert, update, and delete data in the database.
3. **Security Measures**: Implementing security protocols such as firewalls, encryption, and access control.
4. **Performance Optimization**: Monitoring and optimizing database performance for efficient operations.
5. **Scalability**: Exploring options to scale the Azure SQL Database as the e-commerce platform grows.
6. **Documentation**: Comprehensive documentation outlining the setup process, database schema, and key learnings.

Skills Acquired:
- Cloud Computing
- SQL Querying
- Database Management
- Security Implementation
- Performance Monitoring
- Scalability Planning

By completing this project, you will enhance your proficiency in setting up and managing SQL databases in Azure, preparing you for real-world scenarios requiring cloud-based database solutions.


# Steps



**Steps for Installing an Azure Database**:

1. **Sign in to Azure Portal**:
   - Log in to your Azure account at portal.azure.com.

2. **Create a New Resource Group**:
   ![Opera Snapshot_2024-03-29_113133_portal azure com](https://github.com/Malik-444/Azure-SQL/assets/151242422/a378fbf3-9fc4-4803-a70e-790a78688c93)
![Opera Snapshot_2024-03-29_113223_portal azure com](https://github.com/Malik-444/Azure-SQL/assets/151242422/0a5a4edf-d209-4d60-be48-55c649834322)
  - We are just going to name it sql project  and skip the tag section
![Opera Snapshot_2024-03-29_113434_portal azure com](https://github.com/Malik-444/Azure-SQL/assets/151242422/04bdcd10-6027-4f69-8306-e25bc8ce7138)

   - Within the resource group click on "Create a resource" in the Azure portal.
     ![Opera Snapshot_2024-03-29_113537_portal azure com](https://github.com/Malik-444/Azure-SQL/assets/151242422/d065a93d-1c8a-4bf6-9d0f-f3295273919c)
   - Search for "SQL Database" in the marketplace.
    ![Opera Snapshot_2024-03-29_113821_portal azure com](https://github.com/Malik-444/Azure-SQL/assets/151242422/94d766ce-c3fb-45c3-9db4-bf904350b629)

4. **Configure Database Settings**:
   - Specify the database name, subscription, resource group, and server.
   - Resource Group: The one we created for this project
     ![Opera Snapshot_2024-03-29_114007_portal azure com](https://github.com/Malik-444/Azure-SQL/assets/151242422/74172688-a2a9-4375-be2e-66f55b023612)
   - Sever: We are going to create a sever
           Name the SQL Server
           We are going to use the SQL Authentication
           Then we are going to create a password and user to access the server
     ![Opera Snapshot_2024-03-29_114222_portal azure com](https://github.com/Malik-444/Azure-SQL/assets/151242422/65a81774-7cb7-4186-b987-ad99debf15bd)

5. **Choose Deployment Option**:
   - Select the deployment option that suits your needs (Single database, Elastic pool, Managed instance).
       this effects the pricing 
     ![Opera Snapshot_2024-03-29_114552_portal azure com](https://github.com/Malik-444/Azure-SQL/assets/151242422/e10cdbae-5e8d-48c5-90a3-6a0d22b70aa4)


7. **Set Pricing Tier**:
   - Choose the pricing tier based on your requirements (Basic, Standard, Premium).
   - Consider performance levels, storage capacity, and backup options.
     Keeping everything default

8. **Configure Additional Settings**:
   - Networking
       These options so we will be able to access the database withing our own network
      ![Opera Snapshot_2024-03-29_114811_portal azure com](https://github.com/Malik-444/Azure-SQL/assets/151242422/32e50e1b-7714-4664-a6cc-91a1041775f0)
   -Additional Settings
     In this section we are just putting where our data source is coming from , im using sample so the tables would be automatically created but u can do none and create your own tables and data
      ![Opera Snapshot_2024-03-29_114859_portal azure com](https://github.com/Malik-444/Azure-SQL/assets/151242422/78d14f4f-df65-4519-a371-7764149469bf)

9. **Review and Create**:
   - Review all the settings to ensure they are correct.
   - Click on "Create" to deploy the Azure SQL Database.

10. **Access Database**:
   - Once the deployment is complete, access your database in the Azure portal.
   - Use tools like Azure Data Studio or SQL Server Management Studio to connect to the database.
      We are going to use SQL Server Management Studio
     ![Capture](https://github.com/Malik-444/Azure-SQL/assets/151242422/7c8f9fc9-c597-495c-8b15-b2b2ca3b3247)
   -Use your Server Name and Login to get access
      ,server name can be found in your SQl resource (Located in your in resource group
![Opera Snapshot_2024-03-29_115753_portal azure com](https://github.com/Malik-444/Azure-SQL/assets/151242422/49d0c590-5732-402c-a1c2-8ebbb59de09b)
 
11. **Testing Database**:
    - Run a query to make sure everything work and get familiar with the SQL Server Management Studio.
      ![2](https://github.com/Malik-444/Azure-SQL/assets/151242422/924a5ac9-e78a-4d10-ba1a-0cf61e7bad9c)
      1:The Actaul database you are going to be useing you query in (make sure you change databases to match the type of query you are doing)
      2: List of databases
      3:Results of your query
      4:To start a query(queries get saved after exiting studio to be used later)
      5: The actual query we wrote to test out 

12. **Manage and Monitor**:
    - Regularly manage and monitor the database performance using Azure monitoring tools.
    - Optimize configurations for better efficiency and scalability.

By following these steps, you can successfully install an Azure SQL Database and begin using it for your applications or projects.
