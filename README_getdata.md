# Getting a semester of hindcast data, and spoofing the year   

1. Download the .grib2 files from a particular year, for instance 2006 [here](https://noaa-gefs-retrospective.s3.amazonaws.com/index.html#GEFSv12/reforecast/2006/)

2. ChatGPT says:

   You can convert GRIB2 files to NetCDF (.nc) format and then use tools like ncks or ncatted (NetCDF Operators) to edit metadata. Here are the general steps:
   
    • Convert GRIB2 to NetCDF: Use a tool like cdo (Climate Data Operators) or ncl_convert2nc to convert your GRIB2 files to NetCDF format.
       For example, cdo -f nc copy input.grib2 output.nc

    • Edit Metadata with ncks or ncatted (set "year" to 1234 or some other harmless/obvious spoof year)
      • ncap2 or ncatted or ncks are tools for specific metadata modifications. Refer to the documentation of these tools for detailed usage instructions.
