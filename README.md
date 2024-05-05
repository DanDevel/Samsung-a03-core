# Samsung A03 core
send and read AT ATX commands to mobile device
by Igor Azevedo :smiley: - Computational Engineer :rocket:


## Device Info: :warning:

📱 Galaxy A03 Core 

💾 driver: SAMSUNG Mobile USB Modem 

📀 provider: SAMSUNG Electronics Co., Ltd

💾 driver version: 2.19.1.0 


## AT commands to communicate with a modem 📱 

My application utilizes AT commands to communicate with a modem. Here's a brief overview of how it works and what you can do with it:

☎️ AT: This command checks communication with the modem. It's the first step to ensuring that the application can communicate properly with the device.

☎️ ATZ: This command restores the modem's default settings. It's useful if you need to reset the device settings to their default values.

☎️ ATI: Returns detailed information about the modem, including manufacturer, model, and firmware revision. This can be useful for identifying the type of modem being used.

☎️ AT+CGMI: Returns the modem manufacturer, providing a quick way to get basic information about the device.

☎️ AT+CGMM: Returns the specific model of the modem. This can be helpful for distinguishing between different versions from the same manufacturer.

☎️ AT+CGMR: Returns the modem firmware revision. This information is important to ensure you're using the latest version of the device's software.

☎️ AT+CSQ: Returns the signal quality. This is essential for checking signal strength and ensuring a reliable connection.

☎️ ATD<number>: This command makes a call to the specified number. It allows the user to dial a phone number directly from the application.

☎️ ATH: This command hangs up the current call. It's useful for ending a call that's in progress.

☎️ AT+CMGS: This command sends a text message. It allows the user to send text messages directly from the application to other devices.

These are some of the AT commands that my application uses to communicate with the modem. With these functionalities, users can perform a variety of tasks, from checking signal quality to making calls and sending text messages, all from a user-friendly interface.


# Signal strength live monitor :fire:  

## Check the 3G / 4G / 5G signal strength in live mode.

Signal: Get the signal strength and plot the results on a chart component.

Time interval: 60 Seconds

## Example 🖥️  

![clarosSignal2](https://github.com/DanDevel/Samsung-a03-core/assets/65668317/1820dd4d-1731-433c-9053-ff03c34114e3)



# Start here:

1 - Click on COM Port 3

2 - Start using by sending AT commands, you can click on the command list or type on text box the command you want to send. Or monitoring the 3G 4G 5G signal.


## Login screen

![image](https://github.com/DanDevel/Samsung-a03-core/assets/65668317/3515cdc2-aaa5-4ab7-aaaf-b1fb3cb5b94c)



## AT Commands & Live monitor

Commands & live monitor screen 🖥️  

![image](https://github.com/DanDevel/Samsung-a03-core/assets/65668317/d78fea4b-734d-40f6-a205-606b34bc8d3e)







