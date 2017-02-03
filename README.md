# manifest
|Sync Procedure  |                                                                                        |
|--------------: | :--------------------------------------------------------------------------------------|
|1     | repo init -u https://github.com/mj1687/manifest.git -b caf-7.1                                   |
|2     | Now it's time to sync, use this command: repo sync -j# (# is the number of jobs, es -j32)        |



|Know issues on Nexus  | Consider that the problems on Nexus devices are probablly reflected on pixels  |
|-----------: | :--------------------------------------------------------------------------------------|
|1| com.android.phone crash  |
|Solution| Use my fw opt telephony and packages/services/telephony instead of the caf one      |
|2| when you dial something in the dialer and you try to make a call the device crash  |
|Solution| use my packages/services/telecomm instead of the caf one      |

framework_opt_telephony (stay with branch elixium-7.1): https://github.com/mj1687/platform_frameworks_opt_telephony

telephony: https://github.com/mj1687/android_packages_services_Telephony

telecomm (stay with the caf-7.1 branch): https://github.com/mj1687/platform_packages_services_Telecomm


