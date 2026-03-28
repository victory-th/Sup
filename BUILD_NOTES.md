
# Build Notes

This document provides instructions for building the React Native Android application.

## Configuration

The application requires the following environment variables to be set:

- `SUPABASE_URL`: The URL of your Supabase project.
- `SUPABASE_ANON_KEY`: The public, anonymous key for your Supabase project.

These values should be configured in `client-app/VictoryGame/src/api/runtimeConfig.ts`.

## Test Button

The "Test" button in the application triggers a sequence of calls to the Supabase backend to ensure that the integration is working correctly.

## Cloud Build

The Android application is intended to be built in a cloud environment, not in this local workspace. The local environment is not configured for Android builds, and attempting to build locally will likely fail.
