# XUGOU - Lightweight Monitoring Platform Based on CloudFlare

<div align="center">

![XUGOU Logo](frontend/public/logo.svg)

XUGOU is a lightweight system monitoring platform based on CloudFlare, providing system monitoring and status page functionality.

English | [简体中文](./README.md)

</div>

## 📅 Development Plan

Currently implemented features:

- ✅ System Monitoring - Client resource monitoring and data reporting
- ✅ HTTP Monitoring - API endpoint health detection and analysis
- ✅ Data Visualization - Real-time data display and historical trend analysis
- ✅ Status Page - Customizable service status page
- ✅ Alert Notifications - Anomaly event notifications through multiple channels (Email, Telegram, etc.)
- ✅ User Management - Supports user registration, multi-user management, and assignable permissions

## ✨ Core Features

- 🖥️ **System Monitoring**
  - Real-time monitoring of CPU, memory, disk, network and other system metrics
  - Support for custom monitoring intervals
  - Cross-platform support (agent written in Go, supporting all platforms where Go can compile)

- 🌐 **HTTP Monitoring**
  - Support for HTTP/HTTPS endpoint monitoring
  - Custom request methods, headers, and request bodies
  - Response time, status code and content validation

- 📊 **Data Visualization**
  - Real-time data chart display
  - Custom dashboards

- 🌍 **Status Page**
  - Customizable status page
  - Support for multiple monitoring items
  - Responsive design

- 👥 **User Management**
  - Supports new user registration
  - Supports multi-user management
  - Assignable permissions

## 🏗️ System Architecture

XUGOU adopts a modern system architecture, including the following components:

- **Agent**: Lightweight system monitoring client
- **Backend**: Backend service based on Cloudflare Workers
- **Frontend**: Modern frontend interface based on React + TypeScript

## 🚀 Quick Start

### Deployment Guide

Default username: admin  Default password: admin123

[XUGOU wiki Deployment Guide](https://github.com/zaunist/xugou/wiki)

## FAQ

[XUGOU wiki FAQ](https://github.com/zaunist/xugou/wiki)

## ⭐ Support the Author

Sponsor me in any way you can:

- Star the project and share it with your friends
- Gitfish: [Gitfish Sponsor](https://www.gitfish.dev/repo/zaunist/xugou)
- Buy me a coffee

<div align="center">
  <a href="https://buymeacoffee.com/real_zaunist" target="_blank">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" width="200" height="51">
  </a>
</div>

## 🤝 Contribution

All forms of contributions are welcome, whether it's new features, bug fixes, or documentation improvements.

## 🏢 Sponsorship

Thanks to the following sponsors for supporting the development of XUGOU:

[Cloudflare](https://www.cloudflare.com/)

## 📄 License

This project is open-sourced under the MIT License. See the [LICENSE](./LICENSE) file for details. 

## 🔥 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=zaunist/xugou&type=Date)](https://www.star-history.com/#zaunist/xugou&Date)
