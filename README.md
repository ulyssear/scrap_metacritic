

# Metacritic bot scraper

## Installation

1. Clone the repository

```bash
git clone <url-of-this-repository>
```

2. Install the dependencies with npm

```bash
npm install
```

## Usage

```bash
node index.js --executable="chrome" --headless="true"
```

| Parameter | Description | Default value |
| --- | --- | --- |
| bot_name | Name of the bot | 'metacritic' |
| date | Date of the data | Date with this format : "2023-01-01" |
| root_path | Root path of the project | path.resolve('.') |
| data_directory | Directory where the data will be stored | 'data' |
| executable_path | Path to the executable | '' |
| os | Operating system | OS |
| executable | Executable | 'chrome' |
| headless | Headless mode | 'true' |
| start | Index of first task | 0 |
| end | Index of last task | -1 |