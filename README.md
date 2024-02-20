# End to End Project on Snowflake AWS

In this project, we explore how to integrate the Snowflake Data Warehouse with AWS Cloud S3 buckets to access files.

# Data flow diagram:

<img width="987" alt="Screenshot 2024-02-20 at 00 35 23" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/18b68637-4c43-4ccf-84d7-8544c197fdab">


we go to AWS and create a S3 bucket:

<img width="403" alt="Screenshot 2024-02-20 at 00 38 58" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/c5473e0a-12a3-4d76-810a-c2c80129ea0d">

we upload the file customer_info.csv:

<img width="699" alt="Screenshot 2024-02-20 at 00 39 42" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/ee8a5f0b-0aec-4fea-91b1-984eaa560e43">

we go to IAM and create a Policy:

<img width="509" alt="Screenshot 2024-02-20 at 00 41 10" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/7c6041c3-26b1-46d5-accf-dea4f3d9b84b">

<img width="582" alt="Screenshot 2024-02-20 at 00 43 21" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/c28aabd9-16ac-4f01-ab39-03aecaac60f1">

we create an AWS account.

<img width="518" alt="Screenshot 2024-02-20 at 00 45 01" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/3bc4eba2-d222-47f2-8fa2-a53b4a3b0060">

we go now to Snowflake:

<img width="604" alt="Screenshot 2024-02-20 at 00 46 36" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/cdecf329-5275-47bd-b178-7ba4a95fed3d">

we create an integration:

<img width="437" alt="Screenshot 2024-02-20 at 00 49 41" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/8b4b0d4e-9184-42dd-bc82-7969dcd5b401">

<img width="487" alt="Screenshot 2024-02-20 at 00 50 00" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/103e727f-a08c-412b-b50b-17907f94496a">

<img width="535" alt="Screenshot 2024-02-20 at 00 50 28" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/05150638-a309-4b65-a95e-8a1326494b10">

we edit the policy with snowflake_external_id

<img width="428" alt="Screenshot 2024-02-20 at 00 55 01" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/16d36c3a-df4d-4554-848e-f16575ae3fed">

<img width="977" alt="Screenshot 2024-02-20 at 00 55 21" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/b63b88e4-5acd-45e6-ab4c-315cacf0bff0">

<img width="361" alt="Screenshot 2024-02-20 at 00 57 31" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/4d1375d6-c9ec-4c66-a663-a79e785f65a3">

<img width="312" alt="Screenshot 2024-02-20 at 00 59 13" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/de29bf82-ccc0-418d-8a21-935321f17c8d">

<img width="521" alt="Screenshot 2024-02-20 at 00 59 35" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/7c1aff02-a12e-44b0-ad53-0efbfbfd5b96">

<img width="327" alt="Screenshot 2024-02-20 at 00 58 20" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/674ca183-6b35-4c09-a6d7-5c4625f4c45f">

we create a temp table:

<img width="380" alt="Screenshot 2024-02-20 at 01 00 33" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/1e058151-2db2-4942-9f47-f9d0efcd9595">

<img width="507" alt="Screenshot 2024-02-20 at 01 02 07" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/d0a0ff46-f34f-4dbf-b9f0-e96062aace06">

<img width="552" alt="Screenshot 2024-02-20 at 01 03 51" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/e6dec9b0-d6c3-48c7-bb60-e091153a37f6">

<img width="347" alt="Screenshot 2024-02-20 at 01 04 39" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/e9247242-141f-48f9-a6eb-79fa421bed35">

<img width="312" alt="Screenshot 2024-02-20 at 01 05 13" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/4d484d4b-f04f-4389-9983-1cfc093bb187">

<img width="299" alt="Screenshot 2024-02-20 at 01 06 34" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/dafc20cd-0e2d-498a-9b42-25f4675d9d80">

<img width="469" alt="Screenshot 2024-02-20 at 01 07 45" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/04bfdf59-3409-418e-ad2b-5d25de6ca906">

<img width="![Uploading Screenshot 2024-02-20 at 01.04.58.png…]()
388" alt="Screenshot 2024-02-20 at 01 01 14" src="https://github.com/redjules/End-to-End-Project-on-Snowflake-AWS/assets/106017493/af3ecf55-1e29-496c-8d35-c3eea55a82ed">
