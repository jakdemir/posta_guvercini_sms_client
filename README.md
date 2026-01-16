# Posta Güvercini SMS Client

A robust Java client for the Posta Güvercini SMS API (Turkcell partner).

## Overview

Posta Güvercini is one of the major SMS gateway partners of Turkcell in Turkey. This project provides a clean Java client library for integrating with their SMS API.

## Features

- Send SMS messages via HTTP POST
- XML-based API communication
- Easy integration into Java applications

## Technologies

- Java
- XML
- HTTP POST

## Usage

```java
PostaGuverciniClient client = new PostaGuverciniClient(username, password);
client.sendSMS(phoneNumber, message);
```

## Configuration

You'll need valid Posta Güvercini API credentials to use this client.

## Author

Jak Akdemir
