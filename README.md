# haleon
Commandine

    # Start openHAB (background service)
    sudo /bin/systemctl start openhab.service

    # Learn about the current service status
    sudo /bin/systemctl status openhab.service

    # (Re-)Start openHAB (background service)
    sudo /bin/systemctl restart openhab.service

    # Stop the openHAB background service
    sudo /bin/systemctl stop openhab.service

    # Get the service log since the last boot
    sudo journalctl -u openhab.service -b

    # Make openHAB automatically start after booting the Linux host
    [openHAB] Please use the following commands to launch openHAB on a system restart.
            sudo /bin/systemctl daemon-reload
            sudo /bin/systemctl enable openhab.service



Login

    pi
    raspberry
    termius ssh port 22
    openhab port 8080


<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>
