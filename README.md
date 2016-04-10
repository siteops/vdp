# vdp
Enable MySQL Binlog to Kafka event queue, with admin console/management
Product Plan:
1. support of standard MySQL 5.5/5.6/5.7 and MariaDB 5.5/10;
2. support majority of MySQL datatype;
3. Support Kafka as MSG queue data storage; 
4. plan to support RabbitMQ as data storage in V2;
5. Admin functions include:
		a.  list of Database/Tables on website;
		b.  list of tables/queues already imported into VDP platform;
		c.  list of queues already created by VDP;
		d.  create msq queue without login to system;
		e.  list the consumer of msq queues created by VDP;
		f. 	Balance of VDP instances across vdp cluster; 
		g.  restart VDP instance on any crash(VDP instance , or VDP cluster nodes);
		h.	health check function: vdp msg dashboard; (source ip, msq queue name, backlog, msg per second, msg avg size, )
		i.	support of multiple sharded table into one queue(topic), like 128 shard MySQL table order into one msg queue;
		
