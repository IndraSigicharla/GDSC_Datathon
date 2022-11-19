# Files  

#### Train:

*train1.parquet
train2.parquet
train3.parquet*

#### Test:

*test1.parquet
test2.parquet
test3.parquet*

#### Column Names:

```
machine_id - An ID to distinguish between different machines
security_product_name - Antivirus installed in the machine
machine_version - Version of the machine
app_version - Version of the app they use
av_sig_version - Version of the anti-virus pack they use. For example: There are different packs of McAfee
is_beta - Is the product a beta version
rtp_state - RTP stands for Real-time Transport Protocol
is_sxs_passive - NA
av_status - Status of the anti-virus
av_prod_installed - NA
av_prod_enabled - NA
has_tpm - True if machine has tpm
country_id - Country of the machine
city_id - City of the machine
org_id - ID of the organization it belongs to
geo_id - Geometric location ID
local_name_id - Identifier of the user in local English name
platform - Calculates platform name (of OS related properties and processor property)
processor - This is the process architecture of the installed operating system
os_version - Version of the Operating System
os_build - Build of the current OS
os_suite - Product suite mask for the current Operating System
os_ptfm_sub_release - Returns the OS Platform sub
os_build_lab - Build lab that generated the current OS. Example: 9600.17630.amd64fre.winblue_r7.150109
sku_edition - Maps MSDN to SKU
is_protected - Checks if there are any AV protects enabled
auto_sample_opt_in - NA
pua_mode - Mentions the PUA status of the service
s_mode - Mentions if apps from untrusted developers can be installed or not
ie_ver_id - NA
smart_screen - Displays the smart screen string obtained from registry
firewall - Shows the firewall status of the device
uac_luaenable - Shows if the user type is authorized by the admin in the User Access Control panel
mdc2_form_factor - Mentions the form factor of the device
device_family - Mentions the device class
name_id- NA
model_id - NA
core_count_processer - Count of logical cores in the processor
manufacturer_id - ID of manufacturer
model_id - NA
processor_class - Processor class according to price
disk_capacity - Disk space available on the machine in megabytes
disk_type - The disk type of the primary storage
system_volume_capacity - Partition size of the volume on which the OS is stored, in megabytes
has_optical_drive - Indicates if the device has a disk drive or not
ram_capacity - RAM capacity in megabytes
chassis_type - Describes the chassis type
diagonal_display_size - Diagonal length of display in inches
display_resolution_horizontal - Number of pixels in the horizontal direction
display_resolution_vertical - Number of pixels in the vertical direction
power_profile - Describes the default power profile that came with the machine
battery_type - NA
number_of_charges_for_battery - NA
version - OS version
architecture - OS architecture
branch - OS branch
build_number - OS build number
build_revision - OS revision number
edition - OS edition
sku - OS edition friendly name (currently Windows only)
install_type_name - Mentions the type of installation done
install_language_identifier - NA
ui_locale_identifier - NA
auto_update_opt - NA
os_type_status - NA
state_name - Displays the Genuine State of the Operating System
activation_channel - License Key for a machine
flighting_status - NA
flights_activity - Mentions the flighting status of a machine
flight_ring Mentions the ring that would be receiving flights, if enabled
threshold_choice - NA
malware_status - NA
firmware_manufacturer_id - NA
firmware_version_id - NA
secure_boot_status - Mentions the Secure Boot status of the machine
wim_boot_status - NA
virtual_dev_status - Mentions if the device is actually a Virtual Machine
touch_support - Mentions the touch input capability of the device
pen_support - Mentions the pen input capability of the device
aoac_support - Gives the information about the battery, if it supports AOAC or not
is_gamer - Mentions if the device is a gamer device or not
region_id - NA
```
