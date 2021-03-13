1 - Create a hibernate config file
hibernate.cfg.xml - this file is going to containt the db connectivity properties

2 - Create an object class, like Student and annotate it to map the class properties with that of table columns

3 - Create an application class and perform following steps
	a - Create a SessionFactory which will pull connection property info from hibernate.cfg,xml and also provide the object class whose data needs to be persisted to DB
	b - Create session which uses SessionFactory and contains the data object
	c - Create data object
	d - start trasnsaction
	e - save object to DB
	f - commit transaction
	g - close SessionFactory