# Generate fake test data for Magento

MageFaker is a tool for creating a bunch of bogus customer accounts on a Magento installation using realistic, yet fake, customer data.

![image](http://up.nicksays.co.uk/image/0240281V1D1e/Screen%20Shot%202012-11-27%20at%2000.12.07.png)

### Installation

    git clone https://github.com/punkstar/magefaker.git ~/magefaker
    cd ~/magefaker
    composer install
    echo "alias magefaker=~/magefaker/bin/magefaker" >> ~/.zshrc

### Usage

The following command will create 300 fake customer accounts for the Magento installation at `~/Sites/my/magento/root`.

    magefaker --magento ~/Sites/my/magento/root 300