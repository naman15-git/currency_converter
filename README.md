# Currency_Converter
The core approach uses the USD as a central pivot for all conversions , avoiding the need for every direct pair rate. A Python dictionary ensures instantaneous rate retrieval. Input validation makes the script robust by checking for supported currency codes.
# Project Statement - Currency Converter

## 1. Problem Statement

Travelers, students, and international businesses often need to estimate costs in different currencies. Manual currency calculations can be error-prone, especially when converting between currencies without knowing the direct exchange rate.

This project provides a simple Python-based currency converter that allows users to enter an amount, source currency, and target currency and receive the converted value.

## 2. Scope of the Project

The project focuses on developing a command-line currency conversion application using Python.

The system uses USD as a central pivot currency and stores exchange rates in a Python dictionary. It supports conversion between the currencies available in the exchange-rate dictionary and validates user input before performing the conversion.

The current project uses predefined exchange rates rather than retrieving live rates from an external API.

## 3. Target Users

- Students who need quick currency conversions.
- Travelers who want to estimate expenses in different currencies.
- Users who need a simple command-line currency conversion tool.
- Beginners learning Python programming and dictionary-based data processing.

## 4. High-Level Features

- Accepts the amount to be converted.
- Accepts source and target currency codes.
- Uses USD as the central pivot currency.
- Converts the source currency to USD and then to the target currency.
- Supports multiple currencies through a Python dictionary.
- Handles invalid amount input using error handling.
- Accepts currency codes in uppercase format.
- Displays the converted amount to the user.