# hibernate-learning
1 - Create a hibernate config file

- hibernate.cfg.xml: this file is going to contain the db connectivity properties

2 - Create an object class, like Student and annotate it to map the class properties with that of table columns

3 - Create an application class and perform following steps

- Create a SessionFactory which will pull connection property info from hibernate.cfg,xml and also provide the object class whose data needs to be persisted to DB
- Create session which uses SessionFactory and contains the data object
- Create data object
- start trasnsaction
- save object to DB
- commit transaction
- close SessionFactory
