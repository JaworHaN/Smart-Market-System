# Shelf & Box Placement System

**Shelf & Box Placement System Usage Guide**

---

## Overview

Shelf & Box Placement System is a fully Blueprint-based for Unreal Engine.

Designed to work with products of any size, the system automatically calculates placement, stacking, spacing, and alignment while remaining highly customizable and easy to extend.

---

## Why Shelf & Box Placement System?

* 100% Blueprint Only
* Easy to set up
* Modular architecture
* Product size independent
* Automatic placement calculations
* Automatic stacking support
* Category filtering
* Highly customizable
* Easy to extend
* Developer friendly

---

## Core Classes

The system is built around three main classes:

### Product

Stores all product-specific settings and placement rules.

### Area

Defines shelf or display regions where products can be placed automatically.

### Box

Defines product containers that automatically arrange their contents based on product dimensions.

---

## Area Features

* Automatic spacing calculation
* Product-specific area settings
* Product scale multiplier
* Category filtering support

Areas automatically adapt to products regardless of their dimensions while maintaining consistent placement behavior.

---

## Box Features

* Product size independent
* Adjustable padding settings
* Custom box naming
* Automatic product alignment
* Product filtering support

Boxes automatically calculate the optimal placement layout for contained products.

---

## Product Features

Every product can be customized individually through a flexible set of settings.

### Pivot Support

Supports both:

* Center Pivot
* Bottom Center Pivot

Allowing seamless integration with assets using different pivot setups.

### Product Categories

Products can be assigned to custom categories and used with Area filtering systems.

### Placement Multipliers

Configure how much space a product occupies inside:

* Areas
* Boxes

independently.

### Rotation Settings

Define custom product rotations when placed inside Areas.

### Maximum Stack Count

Control how many instances of a product can be stacked vertically.

### Box Filtering

Restrict products to:

* All Boxes
* Specific Boxes Only

for greater control over placement behavior.

---

## Setup

### Product Setup

1. Create a child from IA_Product
2. Assign the desired mesh.
3. Configure placement settings.
4. Define category and filtering rules if needed.

### Area Setup

1. Place an Area actor inside your shelf or display object.
2. Adjust the Area dimensions.
3. Configure filtering options if required.

The system will automatically calculate product placement based on available space.

### Box Setup

1. Create a child from IA_Box.
2. Assign the desired mesh.
3. Configure box settings.
4. Assign products.

Products will automatically arrange themselves inside the box.

---

### Variable Descriptions

To learn what a variable does, check its Description field in the Details Panel. Most variables include detailed explanations of their purpose and usage.

---

## Extensibility

The entire framework is built using clean Blueprint architecture.

All placement calculations, filtering rules, stacking behavior, and customization options can be modified or extended to fit your project's requirements.

---

## Created By

**Batuu**
