# Joeka AI Content Generator

## Overview

Joeka AI Content Generator is an AI-powered automation workflow built with n8n that helps businesses generate social media content ideas for platforms like Instagram.

The workflow reduces the time spent brainstorming content by using AI to create content ideas and automatically storing them in Google Sheets for future planning.

## Problem

Many businesses struggle to consistently create fresh social media content ideas. Manual brainstorming takes time and can slow down marketing activities.

## Solution

This workflow allows a business to provide a content request, uses OpenAI to generate relevant content ideas, and saves the results into a structured Google Sheet.

## Workflow Architecture

Manual Trigger  
↓  
Edit Fields (Input Data)  
↓  
OpenAI (Generate Content Ideas)  
↓  
Edit Fields (Format Output)  
↓  
Google Sheets (Store Results)

## Tools Used

- n8n
- OpenAI API
- Google Sheets

## Skills Demonstrated

- AI workflow automation
- API integration
- Data mapping
- Expression handling in n8n
- Google Sheets automation
- Workflow debugging

## Challenges & Lessons Learned

The main challenge was configuring the Google Sheets node.

I learned how to:
- Map workflow data into spreadsheet columns
- Understand the difference between Append Row and Append/Update Row
- Structure AI outputs before sending them to external applications

## Result

A working AI content generation system that businesses can use to create and organize social media content ideas.

## Status

Completed ✅
