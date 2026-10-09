# Surveillance Pricing Simulator

### ILLUSTRATIVE WORK · NOT AN AIRLINE PRICING ENGINE · EDUCATIONAL PURPOSES ONLY

## Try Here!
[Surveillance Pricing Simulator](https://tolgakurtuluss.github.io/surveillance-pricing/)

## Overview

This interactive demo is a simplified model within the field of Airline Revenue Management, illustrating how user-level signals—gathered while a user shops—can alter the fare displayed for a specific flight. Unlike traditional pricing based on seat availability and timing, this simulator highlights a **person-centric** pricing mechanism.

## Features

*   **Dynamic Pricing:** Experience fares that shift based on passenger profiles and active personal signals.
*   **Anonymous Base Pricing:** Compare personalized fares against traditional pricing models based on seat scarcity and timing.
*   **Personalization Gap:** Visualize the difference between the personalized fare and the anonymous base fare.
*   **Passenger Signals:** Observe the impact on fares by toggling various personal signals (device, number of repeat searches, referral channel, loyalty tier, location, corporate email, dwell time, comparison site visits, VPN mismatch, abandoned search recovery, incognito mode).
*   **Attribution View:** Examine the specific impact (price increase or discount) of each signal on the fare.
*   **Case Comparisons:** Compare how six different passenger profiles (e.g., blank profile, repeat researcher, Gold loyalty member, corporate traveler) might see different fares for the exact same base inventory. *   **Transparency Guardrail:** A safeguard mechanism that suppresses personalized signals, ensuring that only pricing based on traditional seat and timing logic is displayed.
*   **Session Log:** A record tracking signal changes and their impact on the fare throughout the session.

## How It Works

Traditional airline revenue management primarily prices the **seat**: it responds to booking curves, remaining inventory, and departure time. This simulator demonstrates a different mechanism—pricing the **individual**. It allows signals at the shopper level to alter the price displayed before a seat selection is made.

The attribution view clearly illustrates the mechanism: some signals are modeled as increases in willingness to pay, while others act as conversion incentives. The scenario comparison demonstrates how six different passenger profiles might receive different prices for the exact same inventory situation.
