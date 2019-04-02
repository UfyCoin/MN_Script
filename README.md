# Masternode Setup Guide

If you have old scrip, you have to remove it first for updated wallet installation.

rm masternodeinstall.sh

wget -q https://raw.githubusercontent.com/UfyCoin/MN_Script/master/masternodeinstall.sh

sudo chmod +x masternodeinstall.sh

./masternodeinstall.sh

When prompted to Enter your UnifyCoin Masternode GEN Key.

Paster your Masternode GEN Key and press enter

Wait till Node is fully Synced with blockchain. For check enter below command.

ufy-cli getinfo

When Node Fully Synced enter below command for check masternode status.

ufy-cli masternode status
