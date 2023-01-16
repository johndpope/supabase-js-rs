# supabase-js-rs

Rust bindings for Supabase JavaScript library via WebAssembly.

## Usage

Add `supabase-js-rs` to Cargo.toml

```
supabase-js-rs = { version = "0.1.1" }
wasm-bindgen = "0.2.83"
```

Install `@supabase/supabase-js` as package by adding CDN link to index.html in the root of your crate

```
<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>
```

Build and run

```
trunk serve
```

## Examples

- [x] [Sycamore Auth](https://github.com/wa1aric/supabase-js-rs/tree/master/examples/sycamore-auth)
- [x] [Sycamore Guestbook](https://github.com/wa1aric/supabase-js-rs/tree/master/examples/sycamore-guestbook)
- [x] [Sycamore Realtime](https://github.com/wa1aric/supabase-js-rs/tree/master/examples/sycamore-realtime-chat)
- [ ] Perseus
- [x] [Yew Auth](https://github.com/wa1aric/supabase-js-rs/tree/master/examples/yew-supabase-auth)
- [ ] Seed
- [x] [Leptos OAuth](https://github.com/wa1aric/supabase-js-rs/tree/master/examples/leptos-oauth)
- [ ] MoonZoon

## What I've done so far

- [ ] Auth
  - [x] Create a new user
  - [x] Sign in a user
  - [x] Sign in a user through OTP
  - [x] Sign in a user through OAuth
  - [x] Sign out a user
  - [ ] Verify and log in through OTP
  - [x] Retrieve a session
  - [ ] Retrieve a new session
  - [ ] Retrieve a user
  - [ ] Update a user
  - [ ] Set the session data
  - [x] Listen to auth events
  - [ ] Send a password reset request
  - [ ] Enroll a factor
  - [ ] Create a challenge
  - [ ] Verify a challenge
  - [ ] Create and verify a challenge
  - [ ] Unenroll a factor
  - [ ] Get Authenticator Assurance Level
- [ ] Database
  - [x] Fetch data
  - [x] Insert data
  - [ ] Update data
  - [ ] Upsert data
  - [x] Delete data
  - [ ] Call a Postgres function
  - [x] Using filters
  - [x] Using Modifiers
- [ ] Functions
- [x] Realtime
- [ ] Storage
