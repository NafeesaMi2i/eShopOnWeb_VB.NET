# eShopOnWeb_VB.NET Business Document

## Table of Contents
1. [Introduction](#introduction)
2. [System Architecture](#system-architecture)
3. [Components Overview](#components-overview)
4. [Data Flow](#data-flow)
5. [Validation Logic](#validation-logic)
6. [Assembly Information](#assembly-information)

## Introduction
eShopOnWeb_VB.NET is an online e-commerce web application that serves as a reference architecture for building ASP.NET Core applications. It is designed to showcase best practices and patterns for building scalable, modular, and maintainable web applications. The application allows users to browse products, add them to a shopping cart, and place orders.

## System Architecture
The application is structured into three main projects: ApplicationCore, Infrastructure, and Web.VB. The ApplicationCore project contains the domain model and business logic, serving as the heart of the application. The Infrastructure project provides implementations for data access and other external concerns. The Web.VB project is the entry point for users, handling web requests and presenting data through views.

## Components Overview
### ApplicationCore
The ApplicationCore component defines the business model and rules. It includes entities, services, interfaces, and specifications for the application's core functionality.

### Infrastructure
The Infrastructure component handles data persistence and external services. It provides implementations for interfaces defined in ApplicationCore, such as repositories and data services.

### Web.VB
The Web.VB component is responsible for the user interface and web interactions. It processes user requests, utilizes services from ApplicationCore, and renders views.

## Data Flow
Data enters the system through user interactions with the Web.VB front-end, such as product searches and order submissions. The Web.VB component communicates with ApplicationCore to process the data, which in turn may interact with Infrastructure to persist data to a database or retrieve information.

## Validation Logic
The application employs various validation strategies to ensure data integrity. For instance, the BIC (Business Identifier Code) validation logic in the additional-methods.js file ensures that user input conforms to the ISO 9362 standard for BIC codes.

## Assembly Information
### ApplicationCore
- Version: 1.0.0.0
- Company: ApplicationCore

### Infrastructure
- Version: 1.0.0.0
- Company: Infrastructure

### Web.VB
- Version: 1.0.0.0
- Company: Web.VB
