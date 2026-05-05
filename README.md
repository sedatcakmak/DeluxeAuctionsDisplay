# DeluxeAuctionsDisplay

Display addon for **DeluxeAuctions**. Renders ongoing auctions in-world
so players can see them without opening the auction GUI.

## Features

- In-world display of auction items and prices
- Configurable display layout and refresh
- Folia supported

## Requirements

- Spigot / Paper / Folia (API 1.13)
- Java 8 or newer
- **DeluxeAuctions** (hard dependency)

## Commands

- `/auctiondisplay` (aliases: `/deluxeauctionsdisplay`, `/ahdisplay`, `/aucdisplay`) — display management

## Installation

1. Make sure `DeluxeAuctions.jar` is already installed and working.
2. Drop `DeluxeAuctionsDisplay.jar` into your server's `plugins/` folder.
3. Start (or restart) the server to generate the default configuration.
4. Edit `plugins/DeluxeAuctionsDisplay/` to taste, then reload or restart.

## Configuration

Display positions, item formatting and refresh interval are configured
through the YAML files generated under `plugins/DeluxeAuctionsDisplay/`.

## License

See `LICENSE`.
