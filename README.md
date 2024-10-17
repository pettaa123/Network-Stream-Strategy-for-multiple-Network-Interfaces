# Network Endpoint Actors for Machines having multiple Network Interfaces

This repository enhances the functionality of the Network Endpoint Actors by making them usable on host PCs with multiple network adapters. The main goal is to address an issue where the original `Listener:Connect.vi` uses a string-to-IP function that does not return the correct adapter address.

## Features

- Replaces the existing string-to-IP function in `Listener:Connect.vi` with a specified address.
- Ensures that the correct network adapter address is used when connecting, allowing for more reliable networking on systems with multiple adapters.

## Installation

1. **Download the Network Endpoint Actors:**  
   You can find the official version of the Network Endpoint Actors [here](https://www.ni.com/en/support/downloads/tools-network/download.network-endpoint-actors.html#479440).

2. **Replace the Files:**  
   Simply replace the files in your installation with those provided in this repository.

3. **Verify the Changes:**  
   After replacing the files, make sure to verify that your application connects using the correct network adapter.

## Usage

Once the replacement is complete, you can utilize the Network Endpoint Actors as you normally would, with the added benefit of ensuring that the correct adapter address is used for connections.

## Contributing

If you have suggestions for improvements or additional features, feel free to open an issue or submit a pull request!

## License

This project is licensed under the MIT License. See the LICENSE file for more details.