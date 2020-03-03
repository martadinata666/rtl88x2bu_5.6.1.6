Initial commit

Pulled source from http://www.cudytech.com/wu1200_software_download
as per version rtl88x2BU_WiFi_linux_v5.6.1.6_35492.20191025_COEX20180928-6a6a

Add Fix Kernel 5.6.1.6

Add additional USB devices based on RTL8822BU taken from https://github.com/cilynx/rtl88x2bu

Supported Devices :
{USB_DEVICE_AND_INTERFACE_INFO(0x13b1, 0x0043, 0xff, 0xff, 0xff), .driver_info = RTL8822B}, /* Alpha - Alpha*/

{USB_DEVICE_AND_INTERFACE_INFO(0x2001, 0x331c, 0xff, 0xff, 0xff), .driver_info = RTL8822B}, /* Dlink DWA-182*/

{USB_DEVICE_AND_INTERFACE_INFO(0x2357, 0x012d, 0xff, 0xff, 0xff), .driver_info = RTL8822B}, /* TP-Link Archer T3U V1 */

{USB_DEVICE_AND_INTERFACE_INFO(0x2357, 0x0115, 0xff, 0xff, 0xff), .driver_info = 
RTL8822B}, /* TP-Link Archer T4U V3 */

{USB_DEVICE_AND_INTERFACE_INFO(0x7392, 0xB822, 0xff, 0xff, 0xff), .driver_info = RTL8822B}, /* Edimax EW-7822ULC */

{USB_DEVICE_AND_INTERFACE_INFO(0x7392, 0xC822, 0xff, 0xff, 0xff), .driver_info = RTL8822B}, /* Edimax EW-7822UTC */

{USB_DEVICE_AND_INTERFACE_INFO(0x0b05, 0x1841, 0xff, 0xff, 0xff), .driver_info = RTL8822B}, /* ASUS AC1300 USB-AC55 B1 */

{USB_DEVICE_AND_INTERFACE_INFO(0x0b05, 0x184c, 0xff, 0xff, 0xff), .driver_info = RTL8822B}, /* ASUS USB-AC53 Nano */
