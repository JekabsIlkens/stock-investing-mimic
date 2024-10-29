# Stock Investing Mimic (SIM)

<img align="right" alt="SIM-LOGO" width="350px" src="https://i.postimg.cc/9QMG9sbb/sim-logo-nobg.png"/>

Paper investing in stocks using real market data from Polygon.io, with a unique upgrade system 
that lets you reinvest paper earnings to unlock additional investment slots and leverage.
This project demonstrates raw PHP skills, object-oriented programming and adherence to 
SOLID principles. Built from scratch without frameworks to showcase my understanding of core PHP concepts.

---

## Used technologies

**Language:** PHP 8.3.12 </br>
**Database:** PostgreSQL 17 </br>
**Style:** Tailwind CSS v3.0 </br>
**Tests:** PHPUnit 11 </br>
**API:** Polygon.io </br>

---

## SIM v1 features list

- [ ] New user creation (registration)
- [ ] Existing user authorization (login)
- [ ] Stock data gathering (from Polygon.io)
- [ ] Stock data display (with filtering) 		
- [ ] Stock comparing (1 to 1 by performance)	
- [ ] Wallet system for users	(with starting capital)	
- [ ] Stock buying and selling (includes shorting)		
- [ ] Dashboard for users (active orders & recent history)
- [ ] Upgrade purchase system (active order slots & leverage)

---

## Branch naming convention

* master
* feature/wallet-system
* bugfix/new-order-issue

---

## Project directory structure

```shell
stock-investing-mimic
├── config/          	  # Config files (db, api, etc.)
├── public/               # Entry point (index.php)
├── src/
│   ├── Controllers/ 	  # Controller classes
│   ├── Models/      	  # Model classes
│   ├── Views/       	  # View templates
│   ├── Services/    	  # Service classes (business logic)
│   ├── Interfaces/  	  # Interface files
│   ├── Repositories/	  # Repository classes (data access)
│   ├── Validators/  	  # Form validation classes
└── tests/          	  # Unit tests
```
