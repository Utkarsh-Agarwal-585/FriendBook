-- MySQL Administrator dump 1.4
--
-- ------------------------------------------------------
-- Server version	5.0.22-community-nt


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8 */;

/*!40014 SET @OLD_UNIQUE_CHECKS=@@UNIQUE_CHECKS, UNIQUE_CHECKS=0 */;
/*!40014 SET @OLD_FOREIGN_KEY_CHECKS=@@FOREIGN_KEY_CHECKS, FOREIGN_KEY_CHECKS=0 */;
/*!40101 SET @OLD_SQL_MODE=@@SQL_MODE, SQL_MODE='NO_AUTO_VALUE_ON_ZERO' */;


--
-- Create schema friendbook
--

CREATE DATABASE IF NOT EXISTS friendbook;
USE friendbook;

--
-- Definition of table `frnd`
--

DROP TABLE IF EXISTS `frnd`;
CREATE TABLE `frnd` (
  `user` varchar(45) NOT NULL default '',
  `frnd` varchar(45) NOT NULL default '',
  `status_` varchar(45) NOT NULL default '',
  `id` int(10) unsigned NOT NULL auto_increment,
  `userintr` varchar(45) NOT NULL default '',
  PRIMARY KEY  (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `frnd`
--

/*!40000 ALTER TABLE `frnd` DISABLE KEYS */;
INSERT INTO `frnd` (`user`,`frnd`,`status_`,`id`,`userintr`) VALUES 
 ('kali','parthy','YES',1,'Education'),
 ('parthy','kali','YES',3,'music'),
 ('nadana','parthy','YES',4,'Sports'),
 ('parthy','nadana','YES',5,'music'),
 ('sandy','parthy','YES',6,'Entertainment'),
 ('jp','parthy','YES',7,'Education'),
 ('parthy','jp','YES',8,'music');
/*!40000 ALTER TABLE `frnd` ENABLE KEYS */;


--
-- Definition of table `recmend`
--

DROP TABLE IF EXISTS `recmend`;
CREATE TABLE `recmend` (
  `id` int(200) unsigned NOT NULL auto_increment,
  `user` varchar(45) NOT NULL default '',
  `recid` varchar(45) NOT NULL default '',
  PRIMARY KEY  (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `recmend`
--

/*!40000 ALTER TABLE `recmend` DISABLE KEYS */;
INSERT INTO `recmend` (`id`,`user`,`recid`) VALUES 
 (6,'jp','4'),
 (7,'parthy','2');
/*!40000 ALTER TABLE `recmend` ENABLE KEYS */;


--
-- Definition of table `regpage`
--

DROP TABLE IF EXISTS `regpage`;
CREATE TABLE `regpage` (
  `name` varchar(45) NOT NULL default '',
  `userid` varchar(45) NOT NULL default '',
  `pass` varchar(45) NOT NULL default '',
  `mail` varchar(45) NOT NULL default '',
  `age` varchar(45) NOT NULL default '',
  `loc` varchar(45) NOT NULL default '',
  `sex` varchar(45) NOT NULL default '',
  `time_` datetime NOT NULL default '0000-00-00 00:00:00'
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `regpage`
--

/*!40000 ALTER TABLE `regpage` DISABLE KEYS */;
INSERT INTO `regpage` (`name`,`userid`,`pass`,`mail`,`age`,`loc`,`sex`,`time_`) VALUES 
 ('parthiban','parthy','123','prema.sekar07@gmail.com','5th april','music','Male','2014-10-06 18:35:44'),
 ('Nadanapathy','nadana','123','nandnapathy@gmail.com','5th april','Sports','Male','2014-10-07 11:30:21'),
 ('Kalicharan','kali','123','kalicharan.btech@gmail.com','2014-10-17','Education','Male','2014-10-07 12:07:19'),
 ('Santhanam','sandy','123','smuhilan@yahoo.com','2014-10-16','Entertainment','Male','2014-10-07 12:07:46'),
 ('jp info tech','jp','123','jpstudcorner@gmail.com','2014-10-16','Education','Male','2014-10-07 17:30:55');
/*!40000 ALTER TABLE `regpage` ENABLE KEYS */;


--
-- Definition of table `service`
--

DROP TABLE IF EXISTS `service`;
CREATE TABLE `service` (
  `id` int(10) unsigned NOT NULL auto_increment,
  `intr` varchar(45) NOT NULL default '',
  `des` varchar(500) NOT NULL default '',
  `rec` varchar(45) NOT NULL default '',
  PRIMARY KEY  (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `service`
--

/*!40000 ALTER TABLE `service` DISABLE KEYS */;
INSERT INTO `service` (`id`,`intr`,`des`,`rec`) VALUES 
 (1,'Sports','Sport is generally recognised as activities which are based in physical athleticism or physical dexterity, with the largest major competitions such as the Olympic Games admitting only sports meeting this definition,','http://en.wikipedia.org/wiki/Sport'),
 (2,'Music','Music is an art form whose medium is sound. Its common elements are pitch (which governs melody and harmony), rhythm','http://en.wikipedia.org/wiki/Music'),
 (3,'Music','Steven Ellison confronts mortality and pushes four genres forward with help from Herbie Hancock, Snoop Dogg, Kamasi ','http://www.allmusic.com/'),
 (4,'Education','Education in its general sense is a form of learning in which the knowledge, skills, and habits of a group of people are transferred from one generation to the next through teaching, training','http://en.wikipedia.org/wiki/Education'),
 (5,'Entertainment','Entertainment is a form of activity that holds the attention and interest of an audience, or gives pleasure and delight. It can be an idea or a task, but is more likely to be one of the activitie','http://en.wikipedia.org/wiki/Entertainment');
/*!40000 ALTER TABLE `service` ENABLE KEYS */;




/*!40101 SET SQL_MODE=@OLD_SQL_MODE */;
/*!40014 SET FOREIGN_KEY_CHECKS=@OLD_FOREIGN_KEY_CHECKS */;
/*!40014 SET UNIQUE_CHECKS=@OLD_UNIQUE_CHECKS */;
/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;
/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
