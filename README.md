# haleon
Commandine

    # Learn about the current service status
    sudo systemctl status openhab.service

    # (Re-)Start openHAB (background service)
    sudo systemctl restart openhab.service

    # Stop the openHAB background service
    sudo systemctl stop openhab.service

    # Get the service log since the last boot
    sudo journalctl -u openhab.service -b

    # Make openHAB automatically start after booting the Linux host
    sudo systemctl daemon-reload
    sudo systemctl enable openhab.service


Login

    pi
    raspberry
    termius ssh port 22
