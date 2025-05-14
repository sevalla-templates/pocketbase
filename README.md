# PocketBase

PocketBase is an open-source realtime backend solution.

## Features

- **Realtime**: Built-in realtime subscriptions for collections and records.
- **Authentication**: User authentication with email/password, and OAuth2.
- **File Storage**: Safely store files locally or in a S3 storage.
- **Extendable**: Extendable via Go and JavaScript hooks.

Read more about PocketBase [here](https://pocketbase.io/docs/).

## Getting started
1. **Sign up**: Create an account on [Sevalla](https://sevalla.com/signup).
2. **Deploy PocketBase template**: Deploy the PocketBase template from the Sevalla dashboard.
3. **Create PocketBase account**: Create a new PocketBase account using the instructions in the runtime logs of your deployed instance.

## Configuration

- `PB_VERSION`: You can use this environment variable to specify the version of PocketBase you want to use. For example, `PB_VERSION=0.28.1` will use version 0.28.1 of PocketBase.