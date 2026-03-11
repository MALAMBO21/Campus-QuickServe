 # Campus QuickServe Ordering System

## Problem Description
A GUI-based Java prototype for Campus QuickServe that takes customer details/order via JOptionPane, calculates subtotal/VAT/discount, and displays a formatted receipt. Demonstrates OOP.

## Program Structure
- **Order.java**: Attributes (name, etc.), constructor, getters, methods: `calculateSubtotal()`, `calculateDiscount()`, `calculateVAT()`, `calculateTotal()`, `generateReceipt()`.
- **QuickServeApp.java**: Main class for inputs, creates `Order` object, shows receipt.

## How I Approached the Problem
1. Set up GitHub/test branch.
2. Built Order class first (OOP core).
3. Added GUI inputs in main.
4. Implemented calculations iteratively (commits).
5. Added discount/encapsulation.
6. Tested outputs matching spec.

## OOP Concepts Used
- **Class vs Object**: `Order` class → instantiated as object in main.
- **Encapsulation**: Private fields + getters.
- **Constants**: `VAT_RATE = 0.15`.
- **Methods**: Multiple for calculations.
  
<img width="743" height="318" alt="Screenshot 2026-03-11 142747" src="https://github.com/user-attachments/assets/92d9ad37-0cf9-4298-92df-052a7ed5cc72" />







