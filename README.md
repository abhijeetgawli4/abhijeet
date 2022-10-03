create database cricket;

use cricket;

create table players(
player_id int,
player_name varchar(255),
country varchar(255),
player_age int,
player_role varchar(255));

select * from players;

insert into players values

(1,"ROHIT SHARMA",'india',20,'BATSMAN'),
(2,"VIRAT KOHLI",'india',21,'BATSMAN'),
 (3,"HARDIK PANDYA",'india',19,'ALL ROUNDER BATSMAN'),
 (4,"RISHAB PANT",'india',18,'BATSMAN'),
 (5,"KL.RAHUL",'india',21,'BATSMAN'),
 (6,"JASPRIT BUMRAH",'india',20,'MEDIUM BOWLER'),
 (7,"BHUVNESHWAR KUMAR",'india',19,'FAST BOWLER'),
 (8,"ARSHDEEP SINGH",'india',20,'FAST BOWLER'),
 (9,"YUZVENDRA CHAHAL",'india',21,'SPIN BOWLER'),
 (10,"DEEPAK CHAHAR",'india',22,'SPIN BOWLER'),
 (11,"M.S.DHONI",'india',25,'WICKET KEEPER'),
 (12,"DINESH KARTIK",'india',24,'WICKET KEEPER'),
 (13,"BABAR AZAM",'pakistan',20,'BATSMAN'),
 (14,"IMUM UL HAQ",'pakistan',21,'BATSMAN'),
 (15,"RIZWAN",'pakistan',22,'BATSMAN'),
 (16,"SHAHID AFRIDI",'pakistan',23,'BATSMAN'),
 (17,"MOHMAAAD HAFI",'pakistan',24,'BATSMAN'),
 (18,"FAKHAR ZAKHAR","pakistan",25,'WICKET KEEPER'),
 (19,"KAMRAN AKMAL",'pakistan',26,'WICKET KEEPER'),
 (20,"YOUNIS KHAN",'pakistan',27,'FAST BOWLER'),
 (21,"ABDUL RAZZUK",'pakistan',28,'FAST BOWLER'),
 (21,"SHARDUL THAKUR",'india',27,'FAST BOWLER'),
(22,"WASHINGTON SUNDER",'india',25,'MEDIUM FAST BOWLER'),
(23,"RAHUL TRIPATHI",'india',26,'BATSMAN'),
(24,"HANUMA VIHARI",'india',27,'BATSMAN'),
(25,"JAYANT YADAV",'india',28,'SPIN BOWLER'),
(26,"KULDEEP YADAV",'india',29,'SPIN BOWLER'),
(27,"UMESH YADAV",'india',30,'FAST BOWLER'),
(28,"MOHMMAD NABI",'afganistan',24,'SPIN BOWLER'),
(29,"MUJIB UR RAHMAN",'afganistan',25,'SPIN BOWLER'),
(30,"RASHID KHAN",'afganistan',26,'SPIN BOWLER'),
(31,"PAT CUMMINS",'australia',27,'FAST BOWLER'),
(32,"ARON FINCH",'australia',28,'BATSMAN'),
(33,"TIM DEVID",'australia',29,'ALL ROUNDER'),
(34,"JOSH HAZELWOOD",'australia',24,'MEDIUM FAST BOWLER'),
(35,"GLEN MAXWELL",'australia',27,'ALL ROUNDER'),
(36,"MITCHELL STARK",'australia',28,'FAST BOWLER'),
(37,"MITCHELL MARSH",'australia',29,'ALL ROUNDER'),
(38,"STEVE SMITH",'australia',30,'BATSMAN'),
(39,"MARCUS STOINIS",'australia',29,'ALL ROUNDER'),
(40,"MATTHEW WADE",'australia',27,'BATSMAN'),
(41,"DAVID WARNER",'australia',26,'BATSMAN'),
(42,"ADAM ZAMPA",'australia',25,'SPIN BOWLER'),
(43,"AB DE VILLIERS",'south africa',32,'BATSMAN'),
(44,"QUINTON DE KOCK",'south africa',29,'WK BATSMAN'),
(45,"DAVID MILLER",'south africa',21,'BATSMAN'),
(46,"LUNGI NGIDI",'soth africa',24,'FAST BOWLER'),
(47,"KAGISO RABADA",'south africa',25,'FAST BOWLER'),
(48,"CHRIS GAYLE",'west indies',37,'BATSMAN'),
(49,"KIERON POLLARD",'west indies',34,'ALL ROUNDER'),
(50,"D.J BRAVO",'west indies',33,'FAST BOWLER');

select * from players;

use cricket;

create table players_info(
serial_no int,
jersey_no varchar(255),
base_price varchar(255),
matches_played varchar(255),
last_ipl_team_played varchar(255));

select * from players_info;

insert into players_info
values(1,10,'10 LAKH',100,'MUMBAI INDIANS'),
(2,9,'9 LAKH',90,'ROYAL CHALLENGERS BANGALORE'),
(3,8,'8 LAKH',80,'KOLKATA KNIGHT RIDERS'),
(4,7,'7 LAKH',70,'CHENNAI SUPER KINGS'),
(5,6,'8 LAKH',60,'RAJASTHAN ROYALS'),
(6,5,'7 LAKH',50,'PUNJAB KINGS'),
(7,4,'6 LAKH',40,'SUNRISERS HYDERABAD'),
(8,3,'5 LAKH',30,'DELHI CAPITALS'),
(9,2,'10 LAKH',100,'MUMBAI INDIANS'),
(10,1,'9 LAKH',90,'ROYAL CHALLENGERS BANGALORE'),
(11,1,'8 LAKH',80,'KOLKATA KNIGHT RIDERS'),
(12,2,'7 LAKH',70,'CHENNAI SUPER KINGS'),
(13,3,'8 LAKH',60,'RAJASTHAN ROYALS'),
(14,4,'7 LAKH',50,'PUNJAB KINGS'),
(15,5,'6 LAKH',40,'SUNRISERS HYDERABAD'),
(16,6,'5 LAKH',30,'DELHI CAPITALS'),
(17,7,'10 LAKH',100,'MUMBAI INDIANS'),
(18,8,'9 LAKH',90,'ROYAL CHALLENGERS BANGALORE'),
(19,9,'8 LAKH',80,'KOLKATA KNIGHT RIDERS'),
(20,10,'7 LAKH',70,'CHENNAI SUPER KINGS'),
(21,1,'8 LAKH',60,'RAJASTHAN ROYALS'),
(22,2,'7 LAKH',50,'PUNJAB KINGS'),
(23,3,'6 LAKH',40,'SUNRISERS HYDERABAD'),
(24,4,'5 LAKH',30,'DELHI CAPITALS'),
(25,5,'10 LAKH',100,'MUMBAI INDIANS'),
(26,6,'9 LAKH',90,'ROYAL CHALLENGERS BANGALORE'),
(27,7,'8 LAKH',80,'KOLKATA KNIGHT RIDERS'),
(28,8,'7 LAKH',70,'CHENNAI SUPER KINGS'),
(29,9,'8 LAKH',60,'RAJASTHAN ROYALS'),
(30,10,'7 LAKH',50,'PUNJAB KINGS'),
(31,1,'6 LAKH',40,'SUNRISERS HYDERABAD'),
(32,2,'5 LAKH',30,'DELHI CAPITALS'),
(33,3,'10 LAKH',100,'MUMBAI INDIANS'),
(34,4,'9 LAKH',90,'ROYAL CHALLENGERS BANGALORE'),
(35,5,'8 LAKH',80,'KOLKATA KNIGHT RIDERS'),
(36,6,'7 LAKH',70,'CHENNAI SUPER KINGS'),
(37,7,'8 LAKH',60,'RAJASTHAN ROYALS'),
(38,8,'7 LAKH',50,'PUNJAB KINGS'),
(39,9,'6 LAKH',40,'SUNRISERS HYDERABAD'),
(40,10,'5 LAKH',30,'DELHI CAPITALS'),
(41,1,'10 LAKH',100,'MUMBAI INDIANS'),
(42,2,'9 LAKH',90,'ROYAL CHALLENGERS BANGALORE'),
(43,3,'8 LAKH',80,'KOLKATA KNIGHT RIDERS'),
(44,4,'7 LAKH',70,'CHENNAI SUPER KINGS'),
(45,5,'8 LAKH',60,'RAJASTHAN ROYALS'),
(46,6,'7 LAKH',50,'PUNJAB KINGS'),
(47,7,'6 LAKH',40,'SUNRISERS HYDERABAD'),
(48,8,'5 LAKH',30,'DELHI CAPITALS'),
(49,9,'10 LAKH',100,'MUMBAI INDIANS'),
(50,10,'9 LAKH',90,'ROYAL CHALLENGERS BANGALORE');

select * from players_info;

use cricket;

select * from players;

select * from players_info;

select player_name,player_age,player_role from players;

select player_name,country,player_age from players where player_age>20;

select player_name,player_age,player_role
from players
limit 30;

select sum(player_age) from players;
select max(player_age) from players;
select min(player_age) from players;
select avg(player_age) from players;
select count(player_age) from players;

select player_name from players
where player_name like'r%';

select player_name from players
where player_name not like'%y';

select jersey_no,matches_played,base_price
from players_info
where jersey_no=4
order by base_price;

select jersey_no,matches_played,base_price
from players_info
where jersey_no=4
order by base_price desc;

select length(player_name),length(country) from players;
select player_name,country,concat(player_name," ",country) from players;
select player_name,country,length(concat(player_name," ",country)) from players;
select upper(country),lower(player_name) from players;
select left(player_name,4),right(country,3) from players;
select player_name,substring(player_name,1,4) from players;

select player_name,country from players
where trim(player_name)='ROHIT SHARMA'
order by player_name;

select players.player_name,players.player_age,players.country,players_info.jersey_no,players_info.last_ipl_team_played
from players
inner join players_info
on players.player_id=players_info.serial_no;

select players.player_name,players.player_age,players.country,players_info.jersey_no,players_info.last_ipl_team_played
from players
left join players_info
on players.player_id=players_info.serial_no;

select players.player_name,players.player_age,players.country,players_info.jersey_no,players_info.last_ipl_team_played
from players
right join players_info
on players.player_id=players_info.serial_no;

create view ROHITSHARMA as
select * 
from players
where player_name = 'ROHI SHARMA';

select 'players' as tb1,player_id from players
union
select 'players_info' as tb2,serial_no from players_info;


select 'players' as tb1,player_name from players
union
select 'players_info' as tb2,base_price from players_info;

select 'players' as tb1,player_name from players
union all
select 'players_info' as tb2,base_price from players_info;

select 'players' as tb1,player_id from players
union all
select 'players_info' as tb2,serial_no from players_info;

select player_age
from players
group by player_age
having player_age>10
order by player_age desc;

select * from players
where player_name in(select player_name from players where player_name='VIRAT KOHLI');

select * from players
where player_name  not in(select player_name from players where player_name='VIRAT KOHLI');
