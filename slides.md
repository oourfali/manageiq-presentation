class: center, middle, inverse

# Present and future of the ManageIQ and oVirt integration

### [Piotr Kliczewski](mailto:pkliczew@redhat.com)
### [Juan Hernández](mailto:jhernand@redhat.com)
#### Jun 6th 2016

---

class: center, middle

# Objective

The objective of this session is to present the work that the oVirt and
ManageIQ teams have been doing together to improve the integration of
both systems for the ManageIQ Darga release, and the plans to improve it
even further for the upcoming release of oVirt 4.

---

## Agenda

These are the items that we will cover in this session:

- [Introduction](#introduction)

- [Improvements for the Darga release](#darga)

- [Future improvements](#future)

- [Demo](#demo)

---

name: introduction
class: center, middle, inverse

# Introduction

???

In this introduction we should very quicly explain what is oVirt and how
other systems can be integrated using the API.

---

# What is oVirt?

- A virtualization platform.

- Manages virtual machines, storage and networks.

- Easy to use web interface, for humans.

- Comprehensive REST API, for other systems.

- Integrated with ManageIQ as a infrastructure provider, via the REST
  API.

???

Worth also mentioning that it is Open Source, and based on KVM and
Linux.

---

name: darga
class: center, middle, inverse

# Improvements for the darga release

---

## Targeted refresh

- What is the current situation with refresh?

- Why was a change needed?

- What was actually changed?

- Why is that good for users/developers?

???

These are some questions that we may want to answer during the
presentation.

---

## Targeted refresh, the architecture

![Diagram](diagram.png)

???

The `diagram.png` file doesn't exist yet, so only the text `Diagram`
will be displayed.

---

## Targeted refresh, the numbers

???

Some numbers to proof the possitive effect of targeted refresh.

---

## Gluster support

---

## Initial support for version 4 of oVirt

- Version 4 of oVirt will support two versions of the API

- Version 3 of the API will be identical to the current one

- New features will only be available in version 4 of the API

- Initial suppport for the API backwards compatibility mode has been
  added, so that Darga will work with version 4 of oVirt

---

name: future
class: center, middle, inverse

## Future improvements

---

## Future improvements

- Gradually swith from the `ovirt` tem to the new oVirt Ruby SDK

---

name: demo
class: center, middle, inverse

## Demo

---

name: what-else
class: center, middle

## What else?

---

class: center, middle, inverse

# Thanks!
