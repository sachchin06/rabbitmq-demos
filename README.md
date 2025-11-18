# RabbitMQ Basics

This repository contains my personal notes and simple examples while learning RabbitMQ from the official documentation. I created this repo to keep track of what I learn and to have a quick reference for the core messaging concepts.

---

## 📘 What’s Included
- Basic explanation of RabbitMQ components  
- Simple producer and consumer examples  
- Tutorials completed from the official RabbitMQ site  
- Small code samples for queues, exchanges, and routing  

---

## 🎯 Purpose
This repo is mainly for **learning and practice**. It helps me understand how message queues work before using them in real applications.

---

## ▶️ How to Run (Example)

Make sure RabbitMQ is running locally or in Docker.

Start RabbitMQ using Docker:

```bash
docker run -d --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3-management
