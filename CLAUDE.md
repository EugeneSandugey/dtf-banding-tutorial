# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## CRITICAL RULES - NEVER VIOLATE

1. **ABSOLUTELY NO AI-GENERATED IMAGES** - DO NOT create, generate, or add ANY AI-generated images to this project. This is the 4th time this has been an issue. 
2. **NO PLACEHOLDER IMAGES** - Do not create placeholder or example images.
3. **REAL IMAGES ONLY** - Only use actual photographs or real screenshots provided by the user.

## Project Overview

This is a DTF (Direct-to-Film) printer banding tutorial and training guide specifically designed for Audley 24" I3200 4-Head DTF Printers with 2W+2C (2 White + 2 Color) configuration. It serves as a comprehensive resource for technicians and employees to diagnose and fix banding issues.

## Serving the Tutorial

To run the tutorial locally:
```bash
cd /home/echo/projects/banding/dtf-banding-tutorial
python3 -m http.server 3000
```

The tutorial will be accessible at http://localhost:3000

## Project Structure

- `index.html` - Single-page tutorial containing all content, styling, and information
- `images/` - Contains 17 reference images showing various banding types, maintenance procedures, and equipment

## Key Technical Focus Areas

The tutorial covers:
1. **Nozzle Check Patterns** - Good vs bad patterns specific to I3200 printheads
2. **Banding Types** - Horizontal, vertical, color-specific, and white ink banding
3. **Audley-Specific Issues** - Registration wheel dust, no low ink alarm, panel access requirements
4. **2W+2C Configuration** - Double white head maintenance requirements
5. **Environmental Requirements** - 50%+ humidity critical for Audley printers

## Audley Printer Specifications

- **Model**: Audley 24" DTF Printer
- **Printheads**: 4 x Epson I3200 (2 White + 2 Color)
- **Print Width**: 24 inches (610mm)
- **Software**: Maintop (default), optional CadLink or Photoprint
- **Print Speeds**: 4-pass: 15 sqm/h | 6-pass: 10 sqm/h | 8-pass: 8 sqm/h
- **Critical Maintenance**: No automatic low ink warnings - requires manual monitoring

## Image Naming Convention

Images follow descriptive naming patterns:
- `DTF_[description]_[date]_[time].png` - Generated reference images
- Specific examples: nozzle checks, banding types, maintenance procedures

## Content Updates

When updating the tutorial:
1. Maintain focus on Audley 2W+2C configuration throughout
2. All maintenance schedules should reflect the double white head requirements
3. Environmental specifications should emphasize 50%+ humidity for Audley
4. Include visual references wherever possible for training effectiveness

## Important Audley-Specific Details

- **White Ink Circulation**: Must run continuously with 2 white heads
- **Registration Wheel**: Requires weekly cleaning to prevent stretched prints
- **Dampers**: Keep spares on hand - not covered under warranty
- **Film Feed Issues**: Common problem causing stretched/duplicated lines
- **Printhead Lifespan**: 1.5-3 years with proper maintenance