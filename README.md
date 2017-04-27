# Collective Downloading

Provides the functionality to download all the files linked to an Aras Innovator's item type at once (as long as the File ItemType is related).

Aras Innovatorのアイテムタイプに紐づくFileを一括ダウンロードする機能を提供します。 ※アイテムタイプのリレーションとして、Fileアイテムタイプが設定されている場合に限ります。

## History

This project and the following release notes have been migrated from the old Aras Projects page.

Release | Notes
--------|--------
[v11SP6](https://github.com/ArasLabs/collective-downloading/releases/tag/v11SP6) | Instructions (in Japanese) are described in the ReadMe.pdf.
[v11SP2](https://github.com/ArasLabs/collective-downloading/releases/tag/v11SP2) | Instructions are described in the ReadMe.pdf.

#### Supported Aras Versions

Project | Aras
--------|------
[v11SP6](https://github.com/ArasLabs/collective-downloading/releases/tag/v11SP6) | 11.0 SP6
[v11SP2](https://github.com/ArasLabs/collective-downloading/releases/tag/v11SP2) | 11.0 SP2

## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch!**

### Pre-requisites

1. Aras Innovator installed
2. Aras Package Import tool
3. **CollectiveDownloading** import package

### Install Steps

1. Backup your database and store the BAK file in a safe place.
2. Open up the Aras Package Import tool.
3. Enter your login credentials and click **Login**
  * _Note: You must login as root for the package import to succeed!_
4. Enter the package name in the TargetRelease field.
  * Optional: Enter a description in the Description field.
5. Enter the path to your local `..\CollectiveDownloading\Import\imports.mf` file in the Manifest File field.
6. Select **jp.co.neo.CollectiveDownloading** in the Available for Import field.
7. Select Type = **Merge** and Mode = **Thorough Mode**.
8. Click **Import** in the top left corner.
9. Close the Aras Package Import tool.

## Usage

Review the [ReadMe-Collective downloading.pdf](./Documentation/ReadMe-Collective downloading.pdf) for information on using the project. {[English translation](./Documentation/ReadMe-Collective downloading-English.docx)}

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Credits

Created by NEOSYSTEM Co., Ltd.
