# DBAII_lab1
1) create directory hr_dir
![Screenshot (1035)](https://user-images.githubusercontent.com/93229250/232538240-97f3b266-6e26-4e3a-aba4-0d718a22287e.png)
![Screenshot (1042)](https://user-images.githubusercontent.com/93229250/232538303-cd24cef0-027c-4999-ab84-9414cb1a0f51.png)

2) export the "HR" schema using data pump utility.
![Screenshot (1040)](https://user-images.githubusercontent.com/93229250/232538542-08842c0d-7d9a-419e-a0f2-f115c59dcd95.png)
![Screenshot (1044)](https://user-images.githubusercontent.com/93229250/232539019-6fd9432d-91a5-4fe6-8a6d-df1f667ae16c.png)

3) import the dump file created from step (2) in the schema hr_dup in tablespace hr_tbs (create it if not created).
![Screenshot (1047)](https://user-images.githubusercontent.com/93229250/232539084-bbea57b7-895d-4442-b7e0-35bf2ebd9e8a.png)

4) import only one table (employees) from dump file created from step (2) in the scott schema.
![Screenshot (1061)](https://user-images.githubusercontent.com/93229250/232541387-f845c0b6-3332-4169-ad2a-148066aa38e4.png)

5) export full database
![Screenshot (1059)](https://user-images.githubusercontent.com/93229250/232540130-3f216cdc-48f1-492f-b219-4460bd67db7c.png)
![Screenshot (1057)](https://user-images.githubusercontent.com/93229250/232540179-c26e9877-dc2d-4dff-aeca-6d5aca00d54f.png)

6) export metadata of table hr.employees.
![Screenshot (1054)](https://user-images.githubusercontent.com/93229250/232540292-b3014ca5-6dc3-410d-a346-5b6c0a37b9e8.png)

7) import this table with name hr.new_employees
![Screenshot (1060)](https://user-images.githubusercontent.com/93229250/232540495-536ec359-45f3-4ea3-8e91-c62b1d020b95.png)
