CREATE A COMPLETE FLUTTER ANDROID ADMIN APPLICATION.

PROJECT NAME:

ANZZZ ADMIN

IMPORTANT:

THIS IS A FLUTTER ANDROID APPLICATION.

DO NOT CREATE:

- Website
- NextJS
- React
- TypeScript
- Tailwind CSS
- NodeJS

ONLY USE:

- Flutter Stable
- Dart
- Material Design 3
- Riverpod
- Dio
- Go Router
- Shared Preferences
- Flutter Animate

TARGET:

Android APK

PACKAGE NAME:

com.anzzz.admin

================================================

PURPOSE

ANZZZ ADMIN is a dedicated administrator application for managing:

- Games
- Configs
- Tweaks
- Optimizers
- APK Versions
- Users
- Banners
- Icons
- Announcements

This application must NEVER expose admin features to the User App.

================================================

DESIGN REQUIREMENTS

Create an extremely premium gaming dashboard.

Inspired By:

- Steam
- Discord
- Modern Gaming Launchers

Theme:

- Pure Dark Background
- Neon Purple Accent
- Cyan Accent
- Glassmorphism
- Smooth Animations
- Premium Cards
- Material Design 3
- Modern Dashboard

Animations:

- Fade In
- Slide In
- Scale Animation
- Skeleton Loading
- Hero Animation

================================================

LOGIN SYSTEM

Create:

Admin Login Screen

Fields:

- Username
- Password

Features:

- Remember Me
- JWT Authentication Ready
- Secure Session Management
- Logout

Create a configurable default admin account for development only.

================================================

BOTTOM NAVIGATION

Dashboard
Games
Configs
Tweaks
Users
Settings

================================================

DASHBOARD

Show beautiful analytics cards:

- Total Games
- Total Configs
- Total Tweaks
- Total Users
- Total Downloads

Recent Activity Feed

Latest Config Uploads

Latest APK Uploads

================================================

GAME MANAGER

Features:

Add Game

Edit Game

Delete Game

Fields:

Game Name

Package Name

Version

Banner

Icon

Description

Status

Featured Toggle

================================================

CONFIG MANAGER

MOST IMPORTANT SECTION

Admin Can:

Add Config

Edit Config

Delete Config

Upload Config Files

Supported:

- ini
- cfg
- json
- zip

Fields:

Config Name

Game

Version

Description

File URL

Target Path

Install Method

Compatibility

Status

Featured

================================================

INSTALL METHODS

Replace File

Copy File

Extract ZIP

Import JSON

================================================

TARGET PATH SETTINGS

Admin controls installation location.

Examples:

/Android/data/com.kurogame.wutheringwaves.global/files/UE4Game/Client/Client/Saved/Config/Android/Engine.ini

/Admin/AndroidData/GameFolder/Config.ini

Store target paths dynamically.

================================================

TWEAK MANAGER

Create beautiful tweak management.

Fields:

Name

Description

Category

Compatibility

Status

Featured

================================================

OPTIMIZER MANAGER

Profiles:

Ultra Performance

Balanced

Battery Saver

Competitive

Custom

Admin can create unlimited profiles.

================================================

APK UPDATE MANAGER

Features:

Upload APK

Version Number

Version Code

Changelog

Download URL

Force Update Toggle

Optional Update Toggle

Release Notes

================================================

BANNER MANAGER

Upload Banner

Replace Banner

Delete Banner

Preview Banner

================================================

ICON MANAGER

Upload Icon

Replace Icon

Delete Icon

Preview Icon

================================================

ANNOUNCEMENT MANAGER

Create Announcement

Edit Announcement

Delete Announcement

Priority Levels

Publish Date

================================================

USER MANAGER

View Users

Search Users

Ban Users

Unban Users

Role Management

================================================

SETTINGS PAGE

API Base URL

Theme Settings

Security Settings

Backup Settings

About App

================================================

API STRUCTURE

Base URL:

https://api.example.com/api

Endpoints:

POST /login

GET /games

POST /games

PUT /games

DELETE /games

GET /configs

POST /configs

PUT /configs

DELETE /configs

GET /tweaks

POST /tweaks

GET /users

GET /version

================================================

PROJECT STRUCTURE

Generate:

pubspec.yaml

lib/main.dart

lib/core

lib/models

lib/services

lib/providers

lib/routes

lib/screens

lib/widgets

lib/themes

lib/utils

================================================

OUTPUT REQUIREMENTS

Generate actual Flutter code.

Generate all screens.

Generate all widgets.

Generate all services.

Generate all models.

Generate all routes.

Generate complete project structure.

The application must compile successfully.

Do not generate web code.

Do not generate placeholders.

Generate a professional production-ready Android admin application.
