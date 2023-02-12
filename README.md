# Neo4j-Data-Modeling

## Getting Started

### Module Overview

- What graph data modeling is.
- How domain knowledge is important for modeling.
- The difference between a graph data model and an instance model.

<br/>

#### What is graph data modeling

**The steps we take to finally get the graph schema that we will be using in our application.**

1. Define the use cases of the application
2. Model the graph on a paper (nodes and relationships)
3. Test the model you made against the use cases
4. Create the cypher queries
5. Test the queries against the use cases
6. refactor the queries to improve performance and best suite the use cases (iterative step)

<br/>

#### Understanding the domain of your application

1. Describe the application in details
2. Identify the users of the application (people, systems)
3. Agree upon the use cases for the application
4. Rank the importance of the use cases
5. Identify the stakeholders and developers of the application

<br/>

#### Types of models

##### Data Model

**Describes the labels, relationships and properties for the graph. It does not have specific data that will be created in the graph.**

![Screenshot_2023-02-12_22-54-06](https://user-images.githubusercontent.com/77200870/218342310-d5e259bf-38d4-4e36-bb66-ede7b092a73d.png)

##### Instance Model

Testing a sample data against the use cases using our graph model.

![Screenshot_2023-02-12_22-55-09](https://user-images.githubusercontent.com/77200870/218342320-809c2b8d-81bf-4dc2-ba99-17b4be7751f1.png)

<br/>

## Modeling Nodes

### Module Overview

- Identifying the entities from your use cases.
- Creating nodes in the graph in support of the data model.

#### Modeling Nodes

**We use nouns in our use cases to define the labels for our nodes**

![Screenshot_2023-02-12_23-08-57](https://user-images.githubusercontent.com/77200870/218342858-d4d4c623-6a1c-4c0b-9e60-f594ce0df3f2.png)

<br/>

**What can node properties be used for?**

1. Uniquely identify a node (with an ID for example)
2. Answering specific details of the use cases
3. Returning data

