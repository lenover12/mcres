# Minecraft Resource Pack Repository

Welcome to the Minecraft Resource Pack Repository! This repository hosts resource pack files for Minecraft, allowing them to be accessed and downloaded via a GitHub Pages link.

## Purpose

This repository serves a dual purpose:
1. **Hosting Resource Packs:** By using GitHub Pages, the resource packs are easily accessible through a hyperlink. This allows Minecraft server administrators to include the link and the SHA-1 hash of the resource pack in their `server.properties` file. This setup automates the checking and downloading of the resource pack when players join the server.
2. **Supporting TeamSeas Initiative:** As part of the TeamSeas fundraiser/charity initiative, players could join a public server and participate in a minigame utilizing a custom resource pack hosted in this repository.

## Usage

### For Server Administrators

To use these resource packs on your Minecraft server:

1. **Find the Resource Pack URL:** Navigate to the GitHub Pages link for the desired resource pack.
2. **Compute the SHA-1 Hash:** Calculate the SHA-1 hash of the resource pack file.
3. **Edit `server.properties`:** Add the URL and SHA-1 hash to the `server.properties` file in your server directory:
    ```plaintext
    resource-pack=<URL_TO_RESOURCE_PACK>
    resource-pack-sha1=<SHA1_HASH_OF_RESOURCE_PACK>
    ```

### Example

If your resource pack is hosted at `https://yourusername.github.io/minecraft-resource-pack/pack.zip` and its SHA-1 hash is `1a2b3c4d5e6f7g8h9i0j1k2l3m4n5o6p7q8r9s0t`, your `server.properties` file should include:
```plaintext
resource-pack=https://yourusername.github.io/minecraft-resource-pack/pack.zip
resource-pack-sha1=1a2b3c4d5e6f7g8h9i0j1k2l3m4n5o6p7q8r9s0t
```

## TeamSeas Initiative

This repository was created as part of the TeamSeas fundraiser/charity initiative. Players were invited to join a public Minecraft server and participate in a minigame designed to support the cause. The resource pack for the minigame was made and hosted through this GitHub Pages repository.

Thank you for supporting TeamSeas and happy crafting!

Feel free to contribute, raise issues, or reach out if you have any questions. Enjoy your Minecraft adventures!

[Visit the GitHub Pages site](https://yourusername.github.io/minecraft-resource-pack/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
