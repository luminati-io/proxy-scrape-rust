[![Promo](https://brightdata.com/static/github_promo_15.png?md5=105367-daeb786e)](https://brightdata.com/?promo=github15) 

# proxy-scrape-rust
Basic API Rust program demonstrating using web scraping over proxy servers

This project demonstrates setting up proxy servers in [Rest Proxy Servers](https://brightdata.com/blog/how-tos/rust-proxy-servers), Proxies protect your digital identity during web scraping by using their IP address, circumventing IP bans and geoblocking.

## Prerequisites
- Rust and Cargo (Installation guide: [Rustup](https://rustup.rs/))
- Nginx (Installation guide: [nginx](https://nginx.org/en/docs/install.html))

## Setup
1. Clone the repository: `git clone git@github.com:luminati-io/proxy-scrape-rust.git`
2. Navigate to the project directory: `cd proxy-scrape-rust`
3. Install dependencies: `cargo build`

## Running the Scraper
Run the scraper using Cargo:
```bash
cargo run
```

## Dependencies
This project utilizes several external libraries to function effectively. Below are the key dependencies:

### 1. Scraper
[Scraper](https://crates.io/crates/scraper) is a Rust crate for parsing HTML documents based on a CSS selector. It leverages the `html5ever` library, which conforms to the HTML5 specification, ensuring robust and efficient parsing capabilities. This library is essential for extracting data from HTML content, making it perfect for web scraping tasks.

### 2. Reqwest
[Reqwest](https://crates.io/crates/reqwest) is an ergonomic, batteries-included HTTP Client for Rust. It supports both synchronous and asynchronous requests and includes features such as JSON and streaming responses. This library simplifies the process of making network requests, handling various HTTP-related tasks efficiently.

### 3. Tokio
[Tokio](https://crates.io/crates/tokio) is an event-driven, non-blocking I/O platform for writing asynchronous applications with Rust. It is built on the Rust's async/await feature, making it straightforward to write scalable and high-performance applications. Tokio is critical for managing asynchronous tasks and timers, especially when dealing with concurrent operations in network services.

For more information and examples on how to use these dependencies, please refer to their respective documentation.
