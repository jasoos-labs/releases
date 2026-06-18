# DumbInsert v1.0

![DumbInsert](DumbInsert/Assets/SplashBanner.png)

DumbInsert is a small Windows helper for repeated text.

If you have to type it more than once, DumbInsert can help.

## What it does

DumbInsert lets you save reusable text rows and insert them into a target window that you explicitly choose.

Basic flow:

1. Open the app where you want text inserted.
2. Click **Set Target** in DumbInsert.
3. Select a saved row.
4. Double-click or use Insert.

DumbInsert is intentionally simple. It is not a command runner, automation platform, database client, browser tool, AI tool, or password manager.

## First run

DumbInsert starts empty.

To load example rows:

1. Open **More**
2. Choose **Reload Tutorial Rows**
3. Follow **More > Start Here**

You can remove tutorial rows later by selecting the **Start Here** bucket and using **More > Delete Visible**.

## Row types

Normal rows use the standard clipboard paste path.

NoCopy rows avoid the clipboard and use direct typing.

Protected rows ask for a password phrase before use. Protected rows are locally encrypted, but DumbInsert is not a password manager or enterprise secrets vault.

List, List2, List3, and 1B1 rows let you work one line or cell at a time from the Current panel.

## Local data

DumbInsert stores user data locally under:

`%APPDATA%\DumbInsert`

Main row storage:

`%APPDATA%\DumbInsert\snippets.json`

Logs:

`%APPDATA%\DumbInsert\logs`

Use **More > Open Data Folder** to open the data folder.

## Backup

Use:

**More > Export All**

This creates a portable backup file for your saved rows.

Use:

**More > Import File**

to restore/import rows.

## Privacy posture

DumbInsert is a local Windows utility. It does not require an online account and does not send your rows to a cloud service.

Your rows, packs, and text are yours.

## License

DumbInsert v1.0 is freeware, not open source.

See `LICENSE.txt`.

## Credits

Copyright © 2026 Pradeep Arora. All rights reserved.

DumbInsert, GeezerCoder, and JasoosLabs are projects/brands of Pradeep Arora.

Built with ChatGPT assistance.
