# lacounty_exploration_1

###This is a developing exploratory map identifying
* Stacked parcels on lots in Los Angeles County. Stacked  (Source: [LA County Assessor Parcels - 2015 Tax Roll | LA County GIS Data Portal](http://egis3.lacounty.gov/dataportal/2016/04/06/assessor-parcels-2015-tax-roll/))

###Definitions
* Stacked Parcel | The [San Diego Geographic Information Source](http://www.sangis.org/news/faqs.html) (SanGIS, a joint powers authority of the City of San Diego and the County of San Diego) has it defined with examples:

> The SanGIS parcel layers are “stacked” parcels. That means that for any piece of ground there may be multiple parcels. 
> For example, a condominium building in downtown San Diego may have 200 individual condos. 
> Each condo is a separate taxable parcel. All 200 parcels will be associated with the same physical lot on the ground. 
> When the SanGIS parcel layer is created each individual condo has a polygon representing the physical location of the parent parcel. 
> In this example there will be 200 polygons all stacked on top of each other that represent the taxable parcels and each polygon will 
> have the same physical characteristics (shape, size, area, location) – they are, essentially, copies of each other. However, other 
> associated information (owner, document numbers, etc.) will be different for each. In this case, each condo unit will have its own 
> parcel number and there will be no single parcel representing the lot on the ground.
> 
> Besides condominiums there are two other cases where you will see stacked parcels – possessory interests and mobile homes. 
> Possessory interest parcel numbers (APNs) start with 76x. A possessory interest (or PI) parcel represents a taxable interest
> in the underlying, or parent, parcel but not necessarily ownership. For instance, a private company may have an arrangement with 
> a University to operate a business on campus – a coffee shop or gift shop for example. The private business is taxable and is 
> assigned a 76x APN that is associated with the parent parcel owned by the University. Possessory Interests do not represent 
> ownership on the parcel, only a taxable interest in the underlying parent.
> 
> Mobile home parcel APNs start with 77x. In a manner similar to the possessory interests, mobile home owners own their home (coach) 
> but not the underlying property on which the house sits. The actual mobile home is a separate taxable parcel associated with 
> the mobile home park parent parcel. These taxable parcels all have the same polygon as the underlying parent parcel and will 
> show as stacked parcels as well.

###Discrepancies
* There may be inaccuracies with the County Data 

###Next Steps
* Perform a City by City analysis of stacked properties comparing percentage of lots.
* Many properties are listed as Condo-Conversions, which could help in determining properties that were once rent-controlled and [Ellis'd](http://www.scpr.org/news/2015/04/28/51259/faq-what-to-do-if-you-re-evicted-through-the-ellis/) (in cities where RSOs are implemented)
* Have a question? Email me, omaru@theworks.la or shoot me a tweet @theworksla
