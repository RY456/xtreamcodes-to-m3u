# Xtream Codes to M3U Converter

A powerful, user-friendly Node.js application that converts Xtream Codes API credentials into an M3U playlist file. It features a modern web interface, multi-language support, and advanced category management.

<p align="center">
  <img src="screenshots/main.png" width="48%" alt="Main Interface" />
  <img src="screenshots/ui.png" width="48%" alt="Category Selection" />
</p>

## 🚀 Key Features

*   **Xtream Codes API Support**: Connects to any IPTV provider using Xtream Codes API.
*   **Multiple Export Formats**:
    *   **M3U** (Standard): Compatible with VLC, Perfect Player, Tivimate, etc.
    *   **M3U8** (Apple/HLS): Optimized for Apple devices and HLS players.
    *   **JSON** (API/Developer): Structured data format for API integrations and custom applications.
*   **Category Management**:
    *   **Fetch & Select**: Retrieve categories from the server and select only what you want.
    *   **Drag & Drop Sorting**: Reorder categories simply by dragging them. The M3U will follow your custom order.
    *   **Bulk Actions**: "Select All" and "Deselect All" buttons for quick management.
    *   **Search**: Instantly filter categories by name using the search bar.
*   **Content Filtering**: Choose to include Live TV, Movies (VOD), Series, or all three.
*   **EPG & Catch-up**: Optional support for Electronic Program Guide (EPG) and Catch-up (TV Archive).
*   **Credential Management**: Save your credentials locally for quick access (browser localStorage).
*   **Account Info**: Displays account status (Active/Trial/Expired), expiry date, and connection limits after fetching.
*   **Modern UI**: Responsive, dark/light theme interface built with Bootstrap 5 and custom CSS.
*   **Multi-Language**: Supports English (EN), Turkish (TR), German (DE), and French (FR).
*   **Docker Support**: Easy deployment with Docker and docker-compose.
*   **Privacy Focused**: No data is stored on the server. Credentials are passed directly to the IPTV provider.

## �️ Installation

### Prerequisites

*   **Node.js**: Version 14.0 or higher.
*   **NPM**: Usually comes with Node.js.

### Steps

1.  **Clone the repository** (or download usage):
    ```bash
    git clone https://github.com/your-repo/xtreamcodes-m3u.git
    cd xtreamcodes-m3u
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    ```

3.  **Start the application**:
    ```bash
    npm start
    ```

4.  **Access**: Open your browser and go to `http://localhost:3000`.

## 📖 Usage

1.  **Enter Credentials**:
    *   **IPTV URL**: Your provider's URL (e.g., `http://example.com:8080`).
    *   **Username**: Your IPTV username.
    *   **Password**: Your IPTV password.

2.  **Fetch Categories**:
    *   Click the **"Fetch Categories & Edit"** button.
    *   The app will verify your credentials and load available Live TV, VOD, and Series categories.
    *   Your account info (status, expiry, connections) will be displayed at the top.

3.  **Customize**:
    *   **Select**: Check the boxes for the categories you want to keep.
    *   **Sort**: Drag and drop category items to change their order in the playlist.
    *   **Search**: Use the search bar to quickly find categories by name.
    *   **Bulk**: Use "Select All" / "Deselect All" buttons for quick management.
    *   **Settings**: Enable EPG, Catch-up, or adjust the number of days to include.
    *   **Export Format**: Choose between M3U, M3U8, or JSON format.
    *   **Remember Credentials**: Check "Remember credentials" to save your settings for next time.

4.  **Download**:
    *   Click **"Download M3U"** to download your customized playlist file.

## ⚙️ Configuration

The application runs on port `3000` by default. You can modify this in `app.js` if needed.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).