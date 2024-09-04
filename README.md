# Kafka-pipelining-using-vault-concourse-pipelines

Continue from pervious repository tasks:

Task 5: pull vault image and create container and make configuration save in docker-compose.
Task 6: pull concourse and db for concourse and make docker-compose update.
        from there itself for pipelining download fly setup to enable pipelining, then git-repo to 
        store files and access via pipeline.
        Make python script for scrapping and to saved data to postgres(concourse-db).
        
        
Task 7: Now combine all tasks and then add those scrap data (pharma industries random 10 
        companies) into kafka-topic and by making sink 
        table as like task4 using glue create job and thow data to sink table as well.For that 
        purpose you will need to enable cdc so creating audit table proceed by functions and  
        trigger will be the approach.

Task 8: From task 7 now our task is to transform the scrap data as like you have to make new 
        columns by using columns of table just by using previous columns relations.
        Create dashboard by using visualization charts and show more insights from table.
        
