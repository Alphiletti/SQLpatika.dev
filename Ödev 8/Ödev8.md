## 1- test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

CREATE TABLE employee (
  id INTEGER PRIMARY KEY,
  name VARCHAR(50) NOT NULL,
  email VARCHAR(100),
  birthday DATE
);

## 2- Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

insert into author (id, name, email, birthday) values (1, 'Annie', 'aelward0@etsy.com', '2021/03/29');
insert into author (id, name, email, birthday) values (2, 'Huntlee', 'hcoom1@homestead.com', '2021/03/26');
insert into author (id, name, email, birthday) values (3, 'Berke', 'bgwatkin2@weibo.com', '2021/08/27');
insert into author (id, name, email, birthday) values (4, 'Niven', 'nyeoland3@flavors.me', '2021/05/11');
insert into author (id, name, email, birthday) values (5, 'Del', 'dryam4@stanford.edu', '2021/10/26');
insert into author (id, name, email, birthday) values (6, 'Thelma', 'tdenekamp5@wikia.com', '2021/08/18');
insert into author (id, name, email, birthday) values (7, 'Janella', 'jblencoe6@google.ru', '2021/03/07');
insert into author (id, name, email, birthday) values (8, 'Jarib', 'jseeney7@zdnet.com', '2021/03/30');
insert into author (id, name, email, birthday) values (9, 'Candi', 'cmallon8@ted.com', '2022/02/07');
insert into author (id, name, email, birthday) values (10, 'Shannah', 'sstanier9@sitemeter.com', '2021/03/01');
insert into author (id, name, email, birthday) values (11, 'Jacqui', 'jmcleana@xrea.com', '2021/12/10');
insert into author (id, name, email, birthday) values (12, 'Agnesse', 'abourhillb@economist.com', '2021/07/06');
insert into author (id, name, email, birthday) values (13, 'Burke', 'brestillc@netvibes.com', '2021/02/25');
insert into author (id, name, email, birthday) values (14, 'Merrill', 'mhollowsd@icio.us', '2021/03/14');
insert into author (id, name, email, birthday) values (15, 'Noni', 'nguinnesse@vimeo.com', '2021/05/08');
insert into author (id, name, email, birthday) values (16, 'Rudolph', 'rscanlonf@phpbb.com', '2021/09/23');
insert into author (id, name, email, birthday) values (17, 'Quinlan', 'qwaiteg@reverbnation.com', '2021/02/09');
insert into author (id, name, email, birthday) values (18, 'Madel', 'mpebworthh@instagram.com', '2021/06/30');
insert into author (id, name, email, birthday) values (19, 'Ulrica', 'udurrancei@europa.eu', '2021/08/30');
insert into author (id, name, email, birthday) values (20, 'Grete', 'gcharpinj@liveinternet.ru', '2021/10/11');
insert into author (id, name, email, birthday) values (21, 'Constantin', 'ceixenbergerk@usda.gov', '2021/09/13');
insert into author (id, name, email, birthday) values (22, 'Giustino', 'gborgl@google.com.au', '2021/12/10');
insert into author (id, name, email, birthday) values (23, 'Ivan', 'ibenbrickm@telegraph.co.uk', '2021/05/23');
insert into author (id, name, email, birthday) values (24, 'Sile', 'sbrinsfordn@sphinn.com', '2022/01/25');
insert into author (id, name, email, birthday) values (25, 'Wilmer', 'wliddleo@bloglines.com', '2021/10/01');
insert into author (id, name, email, birthday) values (26, 'Ardys', 'abyfieldp@ibm.com', '2021/12/05');
insert into author (id, name, email, birthday) values (27, 'Rene', 'rsplevinsq@army.mil', '2021/03/06');
insert into author (id, name, email, birthday) values (28, 'Lillis', 'lcockshootr@telegraph.co.uk', '2021/02/26');
insert into author (id, name, email, birthday) values (29, 'Monti', 'mbudgens@nih.gov', '2021/10/31');
insert into author (id, name, email, birthday) values (30, 'Rianon', 'rpetcht@army.mil', '2021/09/12');
insert into author (id, name, email, birthday) values (31, 'Burton', 'blivicku@friendfeed.com', '2021/08/23');
insert into author (id, name, email, birthday) values (32, 'Giff', 'givoryv@ftc.gov', '2022/02/02');
insert into author (id, name, email, birthday) values (33, 'Sheila-kathryn', 'sbridgnellw@telegraph.co.uk', '2021/10/25');
insert into author (id, name, email, birthday) values (34, 'Chester', 'cbontoftx@unc.edu', '2021/06/02');
insert into author (id, name, email, birthday) values (35, 'Nessie', 'njaniky@sogou.com', '2021/11/08');
insert into author (id, name, email, birthday) values (36, 'Massimiliano', 'mvanderkruiz@last.fm', '2021/04/06');
insert into author (id, name, email, birthday) values (37, 'Cull', 'cbrinkler10@hc360.com', '2021/02/24');
insert into author (id, name, email, birthday) values (38, 'Modesty', 'mplackstone11@cargocollective.com', '2021/04/01');
insert into author (id, name, email, birthday) values (39, 'Gabby', 'gsapir12@woothemes.com', '2021/03/30');
insert into author (id, name, email, birthday) values (40, 'Terrill', 'tpellew13@last.fm', '2021/03/26');
insert into author (id, name, email, birthday) values (41, 'Rosco', 'rvedeneev14@archive.org', '2021/11/18');
insert into author (id, name, email, birthday) values (42, 'Lyell', 'lcandy15@psu.edu', '2021/04/15');
insert into author (id, name, email, birthday) values (43, 'Cherida', 'cridsdole16@sourceforge.net', '2021/12/25');
insert into author (id, name, email, birthday) values (44, 'Arron', 'aeudall17@ibm.com', '2021/02/19');
insert into author (id, name, email, birthday) values (45, 'Leilah', 'ldelayglesia18@csmonitor.com', '2021/04/11');
insert into author (id, name, email, birthday) values (46, 'Max', 'mvanschafflaer19@xinhuanet.com', '2021/07/18');
insert into author (id, name, email, birthday) values (47, 'Anya', 'asiegertsz1a@slashdot.org', '2021/11/27');
insert into author (id, name, email, birthday) values (48, 'Marietta', 'mabsolom1b@devhub.com', '2021/06/11');
insert into author (id, name, email, birthday) values (49, 'Leonid', 'ldowderswell1c@oaic.gov.au', '2021/09/11');
insert into author (id, name, email, birthday) values (50, 'Margarete', 'mmacharg1d@fastcompany.com', '2021/10/24');

## 3- Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

UPDATE employee
SET name = 'XXX',
	birthday = '2025-03-11'
WHERE name LIKE 'B%';

## 4- Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

DELETE FROM employee
WHERE id > 40;