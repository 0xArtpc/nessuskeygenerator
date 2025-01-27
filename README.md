# Nessus Any Key Generator

This Python script allows you to generate Nessus Professional Keys directly without having to fill out the registration form. It simplifies the process and makes it more convenient for users to get started with Nessus.


To generate a Nessus Professional Key using the script, simply run the following command:

```bash
python3 nessuskeygen.py
```

## Start or Stop Nessus

### Linux Command-Line Operation

Start Nessus:

```
# systemctl start nessusd
```

Stop Nessus:

```
# systemctl stop nessusd
```

## Updating the Nessus Key

To update the Nessus key, you can use the following commands:

For all operating systems:

```
nessuscli fix --reset-all
```

### Linux

```
# /opt/nessus/sbin/nessuscli fetch --register xxxx-xxxx-xxxx-xxxx
```


Replace `xxxx-xxxx-xxxx-xxxx` with your new Nessus Professional Key.

Please note that this script is provided for educational purposes only and should be used responsibly and in compliance with the Nessus licensing terms.
