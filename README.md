
# Plugin TimedPermission

Selamat datang di **TimedPermission**! Plugin ini dirancang untuk PocketMine-MP dan memungkinkan Anda memberikan izin sementara kepada pemain.

## Fitur Utama

- **Berikan Izin Sementara**: Tambahkan izin sementara kepada pemain dengan durasi yang ditentukan.

## Cara Instalasi

1. mengunduh plugin.
2. **Pindahkan ke Folder Plugin**: Pindahkan file yang diunduh ke folder `plugins` di server PocketMine-MP Anda.
3. **Restart Server**: Restart server PocketMine-MP Anda dan plugin akan aktif.

## Penggunaan Perintah

### `/timepermission`

- **Deskripsi**: Berikan izin sementara kepada pemain.
- **Sintaks**: `/timepermission <player> <permission> <duration> <unit>`
- **Contoh**: `/timepermission Steve myplugin.permission 10 m`
- **Izin**: `timedpermission.command`

## Pengaturan Izin

- **`timedpermission.command`**
  - Izinkan penggunaan perintah `/timepermission`
  - **Default**: op

## Contoh Penggunaan

1. **Memberikan Izin Sementara**: 
   ```sh
   /timepermission Steve myplugin.permission 10 m
   ```

## Lisensi

Plugin **TimedPermission** dirilis di bawah lisensi [MIT License](LICENSE).

## Kontribusi

Jika Anda ingin berkontribusi pada plugin ini, silakan lakukan pull request atau buka isu di repositori GitHub.

---

## English

# TimedPermission Plugin

Welcome to **TimedPermission**! This plugin is designed for PocketMine-MP and allows you to grant temporary permissions to players using PurePerms.

## Key Features

- **Grant Temporary Permission**: Add temporary permissions to players for a specified duration.

## Installation

1. **Download the Plugin**: Click [this link](#) to download the plugin.
2. **Move to Plugin Folder**: Move the downloaded file to the `plugins` folder in your PocketMine-MP server.
3. **Restart Server**: Restart your PocketMine-MP server and the plugin will be activated.

## Command Usage

### `/timepermission`

- **Description**: Grant temporary permission to a player.
- **Syntax**: `/timepermission <player> <permission> <duration> <unit>`
- **Example**: `/timepermission Steve myplugin.permission 10 m`
- **Permission**: `timedpermission.command`

## Permissions

- **`timedpermission.command`**
  - Allows usage of the `/timepermission` command
  - **Default**: op

## Example Usage

1. **Grant Temporary Permission**: 
   ```sh
   /timepermission Steve myplugin.permission 10 m
   ```

## License

The **TimedPermission** plugin is released under the [MIT License](LICENSE).

## Contributing

If you wish to contribute to this plugin, please submit a pull request or open an issue on the GitHub repository
