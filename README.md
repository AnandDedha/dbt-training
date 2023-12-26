Welcome to your new dbt project!

### Using the starter project

Try running the following commands:
- dbt run
- dbt test


### Commands

- #### **dbt init**

  Command: `dbt init my_project`

  Initializes a new dbt project named `my_project` in the current directory.

- #### **dbt run**

  Command: `dbt run`

  Executes the SQL code defined in your dbt models to create or update tables/views in your data warehouse.

  Command: `dbt run -s v_customers.sql` 

  Execute one model at a time v_customers.sql is the model name
  

 - #### **dbt test**

   Command: `dbt test`

   Runs the tests defined in your dbt project to ensure data quality and integrity.

- #### **dbt deps**

  Command: `dbt deps`

  Installs any required packages or dependencies for your dbt project.

- #### **dbt compile**

  Command: `dbt compile`

  Compiles dbt models into raw SQL without running them in the database. This helps catch syntax errors before execution.

- #### **dbt docs**

  Command: `dbt docs generate`

  Run dbt docs generate to generate the documentation for your project.

  Command: `dbt docs serve`
  
  Run dbt docs serve command to launch the documentation.

#### Example Usage:

```markdown
#### Initializing a dbt Project
```
```
dbt init my_project
```

```markdown
#### Running dbt Commands
```
```
dbt run
dbt test
dbt deps
dbt compile
```

### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [dbt community](https://getdbt.com/community) to learn from other analytics engineers
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices
