# Predicting Blood Donations with Python
*This is based on repository of [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php).*  
*This article was written as part of a Data Science Master task.*  

![alt text](http://joseluisfernandez.me/wp-content/uploads/2020/01/Imagen_destacada_blood-2048x1546.png "predicting blood donations with Python")  

When a person loses high blood from an accident, operation, or has health problems, they may need to receive a blood transfusion.
However, since human blood is a substance that cannot currently be manufactured, it is necessary to obtain it from another person, i.e. a blood donor.
It would be good to have way of predicting which people are most likely to donate blood to them, so then those people could be contacted. You can just call everybody, but what if you had millions of clients? Saving time in useless calls might just save lives.
To help in this area, it would be interesting to get a way to predict which people are most likely to donate blood, so that those people can be contacted at times when there are high needs or low reserves. This could be a way to optimize efforts to prioritize calls to donors most likely to be available.

## Dataset
We are using the Blood Transfusion Service Center Data Set, available at the UCI Machine Learning Repository. This dataset consists of the donor database of Blood Transfusion Service Center in Hsin-Chu City in Taiwan. The center passes their blood transfusion service bus to one university in Hsin-Chu City to gather blood donated about every three months in March 2007, with 748 donor rows, each one included :
1.	**R**ecency — time since last donation (months);
2.	**F**requency — total number of donations;
3.	**M**onetary — total blood donated (cubic centimeters),
4.	**T**ime — time since first donation (months); and
5.	**T**arget — represented here by the binary column stating whether a donor in the database has donated blood in March 2007 (1 = yes, 0 = no).
