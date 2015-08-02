---
layout: note
title: Alfresco Installation
---

Here are some notes to install Alfresco 4.x and above.

###Mysql database

{% highlight sql %}
create database alfresco default character set utf8 collate utf8_bin; 
grant all on alfresco.* to 'alfresco'@'localhost' identified by 'alfresco' with grant option; 
grant all on alfresco.* to 'alfresco'@'localhost.localdomain' identified by 'alfresco' with grant option;
{% endhighlight %}
 
###Configuration

alfresco-global.properties to modifyJava

{% highlight properties linenos %}
### database connection properties ### 
db.driver=org.gjt.mm.mysql.Driver 
db.username=alfresco 
db.password=alfresco 
db.name=alfresco 
db.url=jdbc:mysql://localhost:3306/alfresco
{% endhighlight %}
 
###Solr Installation

The best seems this page that describes it in details: [http://docs.alfresco.com/4.0/tasks/solr-install-config.html](http://docs.alfresco.com/4.0/tasks/solr-install-config.html)