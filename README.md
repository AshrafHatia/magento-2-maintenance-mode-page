# 🚧 magento-2-maintenance-mode-page 🚧

⚓ a Magento 2 Maintenance Mode page Design

![Maintenance Page](Service-Unavailable.gif?raw=true "under maintenance")

## 🤖 Installation

Copy 503.phtml in at pub/errors/default of Your Magento root folder

```python
  Magento_Root_Directory/pub/errors/default/503.phtml 
```

## 💡 How to turn Magento 2 Maintenance Mode ON or OFF?

>Use the magento maintenance CLI command to enable or disable Magento maintenance mode.

Command usage:

- Maintenance mode Enable :

```sh
  | php bin/magento maintenance:enable
```

- Maintenance mode Disable :

```sh
  | php bin/magento maintenance:disable
```

- Maintenance mode Enable List of exempt IP-addresses :

```sh
  | php bin/magento maintenance:enable --ip=127.0.0.1 --ip=127.0.0.2
```


- Maintenance mode remove List of exempt IP-addresses :

```sh
  | php bin/magento maintenance:disable --ip=none
```

## 🔗 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## 📜 License
[MIT](https://github.com/AshrafHatia/magento-2-maintenance-mode-page/blob/main/LICENSE)