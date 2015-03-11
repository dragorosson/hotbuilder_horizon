# hotbuilder_horizon

Clone the hotbuilder_horizon repo and then clone the common hotbulder code into common inside it:
```
git clone https://github.com/dragorosson/hotbuilder_horizon.git
cd hotbuilder_horizon
git clone -b horizon https://github.com/rackerlabs/hotbuilder.git common
```
Now the common code should be in hotbuilder_horizon/common (not hotbuilder_horizon/hotbuilder, and certainly not hotbuilder_horizon/common/hotbuilder!)

Follow the steps to install the hotbuilder like the mistral plugin (https://github.com/stackforge/merlin), replacing "mistral" with "hotbuilder_horizon"
