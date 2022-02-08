# setting-up-custom-domain-verifying-domain-in-AAD

1.	Lets first jump to Azure portal and create DNS Zone with same domain name as one we purchased in first task.
  ![image](https://user-images.githubusercontent.com/98162105/152945367-f5bb6cc3-f60d-48b0-9d5b-13db43714202.png)
 
 
2.	Click create.

  ![image](https://user-images.githubusercontent.com/98162105/152945337-04ee21ed-f098-4cf1-be5e-7071d0632804.png)
 
 
3.	Provide resource group and domain name and click Review+click.
  ![image](https://user-images.githubusercontent.com/98162105/152945294-1e84ff10-b302-43c3-a66b-d93db3575087.png)
   
   
4.	Click create.

  ![image](https://user-images.githubusercontent.com/98162105/152945172-8849616e-6a73-4248-b867-869121e4b70f.png)


 
5.	Copy Name server records one by one and paste it inside the freenom name servers.
  ![image](https://user-images.githubusercontent.com/98162105/152945133-a1fb4217-6ca4-443b-82b2-ea6713f7378c.png)


 
6.	Go to freenom, manage domains.

  ![image](https://user-images.githubusercontent.com/98162105/152945098-a2d43726-5224-4815-b59f-ba7c77aee504.png)

 
 
7.	Click Management tools> name servers.
  ![image](https://user-images.githubusercontent.com/98162105/152945064-2c21e8d8-69e0-418d-926a-3afd595315e9.png)
 
 
 
8.	Use custom name servers and start pasting name servers from Azure DNS Zone to this place.

  ![image](https://user-images.githubusercontent.com/98162105/152944864-d7535f3b-a09c-47d7-9ee5-c449fde0481e.png)
 
  ![image](https://user-images.githubusercontent.com/98162105/152944786-9a163e9e-9807-489b-aada-d35ba223327b.png)

 
 
9.	Now, lets go to Azure AD> custom domains.

  ![image](https://user-images.githubusercontent.com/98162105/152944688-a1895e38-19b3-4a87-a1f8-f0596f9c4c4e.png)
 
 
10.	Add custom domain.

 ![image](https://user-images.githubusercontent.com/98162105/152944486-a46a97a4-8cd2-431d-9bb5-3c01bd290c2c.png)
         
         
11.	Add domain name.

 ![image](https://user-images.githubusercontent.com/98162105/152944320-516ec8b6-0f62-4cf3-a460-02301379251b.png)
 
 ![image](https://user-images.githubusercontent.com/98162105/152944347-41ee936a-eb48-4714-bb3c-4c7b6cf85a84.png)

 
 
12.	Now, next step is to validate domain name. We can do this by copying TXT record from below to our DNS Zone.

 ![image](https://user-images.githubusercontent.com/98162105/152944279-59574e23-776e-4b2d-8531-55fd54da379a.png)

 ![image](https://user-images.githubusercontent.com/98162105/152944186-99c4fbcd-b223-4e12-91d5-89a53f2070a6.png)


13.	Now, paste the record in DNS Zone by creating new TXT record.

  ![image](https://user-images.githubusercontent.com/98162105/152944147-475b64cb-cada-448a-bd2b-9e84f9c5d092.png)
 


14.	Create record

 ![image](https://user-images.githubusercontent.com/98162105/152944092-447b3f83-6ad2-4d2a-a53d-9bb6cf5a0c8e.png)



15.	Now, back in Azure AD custom domain and verify.
 
 ![image](https://user-images.githubusercontent.com/98162105/152944031-6f4bfe8f-d3ac-4b27-bb1d-a77649992009.png)



16. You should see domain name verified.
 
 ![image](https://user-images.githubusercontent.com/98162105/152943999-f41baac9-005c-4ff0-9e57-95da6aab42e3.png)


