---
title: 2019-11-26-mt-daily-log
date: '2019-11-26 12:34:00 -0000'
categories: logbook
---

## CPCS.WTIS
### Send Phase 1 Production Warranty Release #2

* for 20191127 deployment
* approved by Loren (IMT Change Advisory Board)

### Followup UAT Issue - Error when importing Dec19 Loading

Outlook: Wine Tracking Inventory System - Error When Importing Loading of Dec

updated API to show extra info - see which master loading is wrong hit

```javascript
{
    "time": "2019-11-25 17:40:52.141677",
    "errorId": "46702f41-be32-433c-8392-9ea9e3a29e51",
    "userId": "",
    "message": "error.master.loading.mapping.exists.in.another.loading",
    "errorMsgKey": "error.master.loading.mapping.exists.in.another.loading",
    "errorMsgParams": [
        "service class: E",
        "req.sector: TS3",
        "req.effectiveFrom: 20200611",
        "hit.effectiveFrom: 20200701",
        "hit.effectiveTo: 20200710",
        "hit.sector: TS3",
        "hit.month: 7",
        "hit.remark: IMPT-FULL-20191125.17:16:59"
    ],
```

waiting Haru to reply...

## MT.TryHaLa


## Notes
### Spring Boot Migration

Guide:
[https://github.com/spring-projects/spring-booT/wiki/Spring-Boot-2.0-Migration-Guide](https://github.com/spring-projects/spring-booT/wiki/Spring-Boot-2.0-Migration-Guide)
[https://medium.com/gumgum-tech/migration-from-vanilla-spring-mvc-to-spring-boot-cba2aa824e](https://medium.com/gumgum-tech/migration-from-vanilla-spring-mvc-to-spring-boot-cba2aa824e)
[https://www.baeldung.com/spring-boot-migration](https://www.baeldung.com/spring-boot-migration)