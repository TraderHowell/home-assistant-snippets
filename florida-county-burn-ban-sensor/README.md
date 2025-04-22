# Florida County Burn Ban Sensor
Adds a sensor to Home Assistant showing the current burn ban status for a given Florida county.  
The date last updated as shown on the [Burn Ban Public Dashboard](https://ffsfm.maps.arcgis.com/apps/dashboards/1f6572c92f8d41ec860f461ea433819b) is also included as a sanity check.

> [!WARNING]  
> Use at your own risk. Always verify with an official source before burning.

## Setup
Replace `<YOUR_COUNTY_NAME_HERE>` with the name of your county *exactly* as it appears on the Burn Ban Public Dashboard.

> [!NOTE]  
> Perhaps keep `scan_interval` no less than `3600` to avoid being a nusiance. (Don't take this endpoint away from me!)
