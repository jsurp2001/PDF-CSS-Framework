# PDF Style Framework

A lightweight CSS framework designed for creating professional and customizable PDFs. This framework is optimized for styling printable forms, charts, tables, and text elements. It provides utility classes and reusable components for quick and consistent design.

---

## Features

- **Typography Utilities**: Control text alignment, sizes, weights, styles, and transformations.
- **Borders and Spacing**: Easily add borders and adjust margins or padding.
- **Charts**: Create bar charts, pie charts, and more with pure CSS.
- **Printable Forms**: Stylish and flexible designs for forms and tables.
- **Debugging Tools**: Classes for visualizing layouts and nested structures.

---

## Installation

Download the `pdf-style.css` file.

Include in your project

```
<link rel="stylesheet" href="path/to/pdf-style.css">
```

## Usage

### Typography

```
<p class="text-bold text-center">This is bold and centered text.</p>
<p class="text-italic text-right">This is italic and right-aligned text.</p>
```

### Borders

```
<div class="border border-primary">Primary Border</div>
<div class="border-top border-danger">Top Border Only</div>
```

### Spacing

```
<div class="p-3 m-3">Padding 3, Margin 3</div>
```

### Charts

```
<div class="bar-chart">
    <div class="bar bg-primary" style="--bar-height: 70%;">70%</div>
    <div class="bar bg-danger" style="--bar-height: 50%;">50%</div>
</div>
```
