<h1 align="center">ytdlgo - YouTube Downloader</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Go-1.22.7-blue.svg" alt="Go Version">
</p>

<p align="center">
  A simple command-line tool written in Go that allows you to download YouTube videos.
</p>

## 📥 Releases

You can download the latest releases of `ytdlgo` from the [Releases page](https://github.com/your-username/ytdlgo/releases). Each release includes precompiled binary, making it easy to get started without needing to build the project from source and to have Go on your device at all.

Usage:

```./ytdlgo <URL>``` (MacOS, Linux)

```ytdlgo <URL>``` (Windows)

## 🚀 Build from source

1. Install Go on your system if you haven't already.
2. Clone this repository or download the `ytdlgo.go` file.
3. Open a terminal and navigate to the directory containing the `ytdlgo.go` file.
4. Run the following command, replacing `<URL>` with the URL of the YouTube video you want to download:

   ```
   go run ytdlgo.go <URL>
   ```

   The downloaded video will be saved in the same directory as the `ytdlgo.go` file, with the filename being the title of the video.

## 📦 Dependencies

This project uses the following dependencies:

- github.com/kkdai/youtube/v2 - A Go library for downloading YouTube videos.
- github.com/schollz/progressbar/v3 - A Go library for displaying a progress bar during the download.

These dependencies will be automatically downloaded and installed when you run the `go mod tidy` command.

## 📄 License

This project is licensed under the [modified MIT License](LICENSE).
