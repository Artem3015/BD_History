# BD_History
create database Nobility


create table People( 
	PeopleId int,
	Surname varchar(18),
	FirstName int,
	Title int,
	years_of_government int,
	Year int
)

create table Firstname(
	NameId int,
	ChFirstname varchar(255)
)


create table Title(
	TitleId int,
	TitleName varchar(25)
)

insert into Title( TitleId, Titlename)
values 
('1','Удельный боярин'),
('2','Боярин Удельного князя'),
('3','Боярин'),
('4','Московский боярин'),
('5','Служивый Князь'),
('6','Удельный князь'),
('7','Великий князь')


insert into Firstname( NameId, ChFirstname)
values 
('1','Юрий'),
('2','Истома'),
('3','Василий '),
('4','Ерома'),
('5','Борис'),
('6','Елена'),
('7','Светлана'),
('8','Любовь'),
('9','Анна'),
('10','Александр'),
('11','Валерий'),
('12','Лев'),
('13','Владимир'),
('14','Расул'),
('15','Сергей'),
('16','Азат'),
('17','Олег'),
('18','Михаил'),
('19','Марк'),
('20','Дудика')



insert into People( PeopleId, Surname, FirstName, Title, years_of_government)
values	
('7','Мещерский','8','6','13'),
('15','Мещерский','6','6','2'),
('11','Мещерский','11','6','20'),
('9','Мещерский','20','2','15'),
('16','Мещерский','9','3','17'),
('7','Борятинские','14','5','20'),
('11','Борятинские','1','1','5'),
('14','Борятинские','18','3','7'),
('8','Борятинские','17','6','13'),
('18','Борятинские','12','1','2'),
('19','Коркодиновы','4','3','10'),
('17','Коркодиновы','11','1','6'),
('1','Коркодиновы','1','7','20'),
('10','Коркодиновы','19','6','10'),
('13','Коркодиновы','14','5','2'),
('11','Коркодиновы','14','3','15'),
('7','Коркодиновы','5','7','10'),
('1','Засекины','3','1','1'),
('7','Засекины','6','5','6'),
('20','Засекины','20','3','16'),
('3','Засекины','7','1','14'),
('8','Засекины','20','5','3'),
('6','Засекины','14','6','1'),
('8','Засекины','18','3','5'),
('10','Волконские','7','3','14'),
('19','Волконские','14','5','17'),
('1','Волконские','9','4','6'),
('4','Волконские','18','1','14'),
('20','Волконские','8','5','4'),
('19','Бельские','7','4','8'),
('20','Бельские','6','4','1'),
('9','Бельские','16','5','14'),
('5','Бельские','5','5','18'),
('5','Бельские','12','2','13'),
('14','Бельские','10','4','9'),
('14','Дашковы','7','7','12'),
('9','Дашковы','14','5','11'),
('8','Дашковы','15','2','20'),
('5','Дашковы','14','3','17'),
('1','Дашковы','8','7','16'),
('9','Дашковы','18','6','8'),
('4','Дашковы','14','7','16'),
('20','Дашковы','13','6','7'),
('19','Дашковы','14','6','7'),
('9','Мосальские','18','4','4'),
('10','Мосальские','13','4','6'),
('17','Мосальские','15','1','19'),
('20','Мосальские','5','1','13'),
('13','Шеховские','11','6','5'),
('17','Шеховские','18','4','19'),
('2','Шеховские','10','6','17'),
('12','Шеховские','5','2','6'),
('4','Шеховские','14','5','10'),
('17','Оболенские','7','4','19'),
('1','Оболенские','17','4','16'),
('11','Оболенские','7','4','9'),
('20','Оболенские','1','4','10'),
('15','Оболенские','18','1','7'),
('5','Аладьины','19','1','11'),
('12','Аладьины','5','6','16'),
('10','Аладьины','6','3','9'),
('4','Аладьины','1','4','6'),
('7','Аладьины','8','5','13'),
('13','Яновы','5','2','10'),
('6','Яновы','18','2','2'),
('16','Яновы','18','3','14'),
('10','Яновы','5','4','14'),
('17','Яновы','17','5','7'),
('19','Хлоповы','17','6','1'),
('14','Хлоповы','10','5','4'),
('20','Хлоповы','8','5','15'),
('20','Хлоповы','18','5','11'),
('9','Хлоповы','17','1','20'),
('18','Хлоповы','8','5','20'),
('18','Сунбуловы','7','3','4'),
('11','Сунбуловы','1','5','19'),
('13','Сунбуловы','1','3','20'),
('10','Сунбуловы','7','6','12'),
('19','Потёмкины','12','5','7'),
('10','Потёмкины','1','7','5'),
('4','Потёмкины','1','7','16'),
('17','Потёмкины','15','2','2'),
('15','Языковы','13','7','16'),
('16','Языковы','4','3','15'),
('12','Языковы','4','4','15'),
('15','Языковы','16','3','11'),
('16','Языковы','9','5','17'),
('11','Языковы','1','3','3'),
('18','Языковы','9','1','18'),
('1','Языковы','18','6','2'),
('15','Монастырёвы','3','6','14'),
('16','Монастырёвы','10','5','2'),
('1','Монастырёвы','11','5','4'),
('1','Монастырёвы','16','1','16'),
('6','Монастырёвы','15','7','3'),
('19','Истленьевы','7','4','6'),
('18','Истленьевы','7','5','5'),
('20','Истленьевы','13','3','19'),
('1','Истленьевы','20','6','10'),
('19','Чоглоковы','4','3','15'),
('12','Чоглоковы','8','6','17'),
('2','Чоглоковы','15','3','14'),
('7','Чоглоковы','13','7','7'),
('13','Чоглоковы','16','7','13'),
('3','Мансуровы','19','2','11'),
('9','Мансуровы','11','2','4'),
('8','Мансуровы','11','2','2'),
('6','Разладины','9','6','16'),
('11','Разладины','3','7','3'),
('10','Разладины','11','6','13'),
('7','Разладины','7','4','2'),
('11','Разладины','14','2','2'),
('8','Давыдовы','7','4','12'),
('12','Давыдовы','1','3','19'),
('10','Давыдовы','6','4','16'),
('17','Давыдовы','14','4','14'),
('19','Давыдовы','7','1','5'),
('16','Голохвастовы','7','4','2'),
('1','Голохвастовы','6','7','3'),
('20','Голохвастовы','18','7','8'),
('6','Голохвастовы','8','4','14'),
('19','Голохвастовы','10','3','5')

UpDate People 
	Set Year = 0
