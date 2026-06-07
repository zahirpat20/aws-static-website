# AWS Static Website

## Overview
Personal portfolio website hosted entirely on AWS infrastructure.

## Architecture
- **S3** — Stores and serves the website files
- **CloudFront** — CDN that delivers the site globally with HTTPS
- **Route 53** — Custom domain (planned)

## Live URL
https://d1jxvsqaewcsr5.cloudfront.net

## What I Learned
- How to configure S3 for static website hosting
- How bucket policies work in JSON
- How CloudFront sits in front of S3 as a CDN
- Why HTTPS matters and how ACM certificates work with CloudFront

## Cost Estimate
- S3 storage: ~$0.00/month (free tier)
- CloudFront: ~$0.00/month (free tier, 1TB transfer included)
- Total: $0/month on free tier

## Architecture Diagram
(Coming soon)
