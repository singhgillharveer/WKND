# ARIYA Experience Monitor

## Endpoints in use:

Below is the list of all the the endpoints in use for Ariya Experience Monitor, each with list of reports the endpoint is populating,

<table border=1>
<thead>
  <tr>
    <th>Sr.</th>
    <th>Endpoint</th>
    <th>Dashboard View</th>
    <th>Report Name</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1.</td>
    <td><s>viewsOverallNumber</s></td>
    <td><s>Experience Monitor Home</s></td>
    <td><s>Views Overall Number</s></td>
  </tr>
  <tr>
    <td rowspan=3>2.</td>
    <td rowspan=3>viewsTrendGraph<br></td>
    <td>Experience Monitor Home</td>
    <td>Views Trend Graph</td>
  </tr>
  <tr>
    <td>Experience Monitor Home</td>
    <td>Views in last day</td>
  </tr>
  <tr>
    <td>Experience Insights</td>
    <td>Views Trend - Last 4 Weeks</td>
  </tr>
  <tr>
    <td rowspan=2>3<br></td>
    <td rowspan=2>viewsRegionSplitOverallNumber</td>
    <td>Experience Monitor Home</td>
    <td>Views Overall Number</td>
  </tr>
  <tr>
    <td>Experience Monitor Home</td>
    <td>Views Region Split</td>
  </tr>
  <tr>
    <td rowspan=3>4.</td>
    <td rowspan=3>handRaisersRegionSplitOverallNumber</td>
    <td>Experience Monitor Home</td>
    <td>Handraisers Overall Number</td>
  </tr>
  <tr>
    <td>Experience Monitor Home</td>
    <td>Handraisers Region Split</td>
  </tr>
  <tr>
    <td>Handraisers Insights</td>
    <td>NAE Handraisers Overall Number</td>
  </tr>
  <tr>
    <td rowspan=2>5.</td>
    <td rowspan=2>handRaisersTrendGraph</td>
    <td>Experience Monitor Home</td>
    <td>Handraisers Trend Graph</td>
  </tr>
  <tr>
    <td>Experience Monitor Home</td>
    <td>Handraisers in last day</td>
  </tr>
  <tr>
    <td rowspan=2>6.</td>
    <td rowspan=2><s>handRaisersRegionSplit</s></td>
    <td><s>Experience Monitor Home</s></td>
    <td><s>Handraisers Region Split</s></td>
  </tr>
  <tr>
    <td><s>Handraisers Insights</s></td>
    <td><s>NAE Handraisers Overall Number</s></td>
  </tr>
  <tr>
    <td rowspan=2>7.</td>
    <td rowspan=2>NAEHandRaisersTrendGraph</td>
    <td>Handraisers Insights</td>
    <td>NAE Handraisers Trend Graph</td>
  </tr>
  <tr>
    <td>Handraisers Insights</td>
    <td>NAE Handraisers in last day</td>
  </tr>
  <tr>
    <td>8.</td>
    <td><s>NAEHandRaisersCountrySplit</s></td>
    <td><s>Handraisers Insights</s></td>
    <td><s>NAE Top Three Countries</s></td>
  </tr>
  <tr>
    <td>9.</td>
    <td>NAETopThreeGrades</td>
    <td>Handraisers Insights</td>
    <td>NAE Top Three Versions</td>
  </tr>
  <tr>
    <td>10.</td>
    <td>NAETopThreeColors</td>
    <td>Handraisers Insights</td>
    <td>NAE Top Three Colors</td>
  </tr>
  <tr>
    <td rowspan=4>11.</td>
    <td rowspan=4>HandraisersConversion</td>
    <td>Handraisers Insights</td>
    <td>Handraisers All Countries</td>
  </tr>
  <tr>
    <td>Handraisers Insights</td>
    <td>NAE All Countries</td>
  </tr>
  <tr>
    <td>Handraisers Insights</td>
    <td>NAE Top Three Countries</td>
  </tr>
  <tr>
    <td>Handraisers Insights</td>
    <td>NAE All Countries (Dealer Breakdown)</td>
  </tr>
  <tr>
    <td>12.</td>
    <td><s>NAETopDealers</s></td>
    <td><s>Handraisers Insights</s></td>
    <td><s>NAE All Countries (Dealer Breakdown)</s></td>
  </tr>
  <tr>
    <td>13.</td>
    <td>HandraisersGeoCountry</td>
    <td>Handraisers Insights</td>
    <td>Handraisers by Cities across the world</td>
  </tr>
  <tr>
    <td>14.</td>
    <td>globalTrafficVLP_Visits</td>
    <td>Experience Insights</td>
    <td>Vehicle Landing Page Views</td>
  </tr>
  <tr>
    <td>15.</td>
    <td>globalTrafficVCVisits</td>
    <td>Experience Insights</td>
    <td>Virtual Car Page Views</td>
  </tr>
  <tr>
    <td>16.</td>
    <td>globalTrafficWPVisits</td>
    <td>Experience Insights</td>
    <td>The Nissan Next Page Views</td>
  </tr>
  <tr>
    <td>17.</td>
    <td>globalTrafficPaidOrganicVisits</td>
    <td>Experience Insights</td>
    <td>Paid/Organic Visits</td>
  </tr>
  <tr>
    <td>18.</td>
    <td>socialNetworksDrillDown</td>
    <td>Experience Insights</td>
    <td>Referrer Type Drill-Down</td>
  </tr>
  <tr>
    <td>19.</td>
    <td><s>visitsTrendLast2Weeks</s></td>
    <td><s>Experience Insights</s></td>
    <td><s>Visits Trend - Last 4 Weeks</s></td>
  </tr>
  <tr>
    <td>20.</td>
    <td>mostPopularMomentsVc</td>
    <td>Experience Insights</td>
    <td>Most Popular Moments on Virtual Car</td>
  </tr>
  <tr>
    <td>21.</td>
    <td>mostPopularFramesVlp</td>
    <td>Experience Insights</td>
    <td>Most Popular Content on Vehicle Landing Page</td>
  </tr>
</tbody>
</table>

## Release notes:

- **Deleted Endpoints:** These endpoints are no longer in use and the their corresponding resports should point to other existing endpoints mentioned
  - *viewsOverallNumber* -> *viewsRegionSplitOverallNumber*
  - *handRaisersRegionSplit* -> *handRaisersRegionSplitOverallNumber*
  - *NAEHandRaisersCountrySplit* -> *HandraisersConversion*
  - *visitsTrendLast2Weeks* -> *viewsTrendGraph*
  - *NAETopDealers* -> *HandraisersConversion*
  
- **Updated Endpoints:** Below endpoints are updated to move data granularity to daily (few are updated by merging deleted endpoints data in them)
  - *viewsTrendGraph*: 
    - Changed to standard reporting instead of real-time
    - Data granularity changed to daily instead of hourly 
    - Will pull data for last 4 weeks (till yesterday)
    - Populates daily view trend and views in last day reports