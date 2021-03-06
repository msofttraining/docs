# How to use an API Consumer

To obtain API Consumer access, please contact our Help Desk support@learnondemandsystems.com for assistance.

If you already have API Consumer access, and would like to use an API consumer with Lab on Demand (LOD), you must configure the API on the lab profile, lab series, and the organization profile that will be used with API calls. For more information on how the API can be used, have a look at our [API Documentation](lod/lod-api/lod-api-main.md). 

- [Lab Series](#lab-series)
- [Lab Profile](#lab-profile)
- [Organization Profile](#organization-profile)

## Lab Series

The lab series must be published to the API consumer that will be used. By publishing a lab series to an API Consumer, that API Consumer will be able to launch any current and future lab profiles that belong to that series. 

To publish the Lab Series:

1. Navigate to the lab series that houses that lab profile that will be used with the API.
1. Click **edit**.
1. On the **Publish** tab, select the API consumer that you wish to publish the lab series to. 
1. Click **Save**.

## Lab Profile

A lab profile must be associated with a lab series, to use the lab profile with an API.

To associate your lab profile with a lab series:

1. Navigate to the **lab profile** you wish to use.
1. Click **Edit profile**.
1. One the **Basic Information** tab, click the Choose button next to Lab Series.
1. Enter the **name** of the lab series you wish to associate the lab profile with, and click **Search**. 
1. Select the lab series and click **Ok**.
1. Click **Save**.

## Organization Profile

The API Consumer needs to be made available to the organization that will use it. This should be the same organization that the lab series and lab profile belong to. 

To make the API Consumer available:

1. Navigate to the Organization profile of the organization that will use the API Consumer. 
1. Click **Edit**.
1. Click the **API Consumer Availability** tab
1. Click **Add API Consumer**
1. Enter the **Name** of the organization, and click **Search**.
1. Click the **Organization** and click **OK**.
1. Click **Save**.

Your API Consumer is now setup and is ready to use. If you would like to view the various ways you can interact with LOD via API, have a look at our [API Documentation](lod-api/lod-api-main.md).
