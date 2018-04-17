# MIS Demo
## 2018-04-16 - PM

### Welcome
* Intros
    * MD - Chris McLaughlin
    * Product Manager - Mark Pocock

* Started emergency services sector
    * Mapping & C&C systems.
    * 80% of GB covered

* 30 years in housing

* Australian based guy for OOH support

* GDPR Compliant

### System demo

* Single database
    * No mess of interfaces
* APIs available everywhere

* Client based
    * Web interface at end of year
* No deletions from database for auditing
* Snapshots and dashboards
    * Live by exception dashboard at startup, no more reports for filtering
    * Realtime KPIs on front screen
* Modules
    * Built up as required
    * Case processing
        * ASB, Complaints, Adaptations, RTB, ME, ***VOIDS***
    * Contractors
    * Rent accounts
    * Repairs
    * Scheme accounting - service charges
    * Stock Management - Van stock
    * Self-service portals

* CRM
    * Call entry
        * Consistent view for 1st point of contact
        * CTI Compliant
        * Workflow
            * All across the system
            * Statement request example
        * Storyboard - Visual prompts for circumstances
            * TAB - Basic info
                * Warning notes, advice notes
                * Property flags - gas servicing
                    * Defect warnings, two cards
                * Rents - UC, DD, Account status (Green/Red), Notice scroll, Legal case
                * System alerts - rents need to contact, surveys, ASB
                * Alerts - Dogs, Pears, Females only, substance abuse
                * Open items - open repairs, complaints, etc
                * Rent account, account actions (arrears actions)
                * No box, no warnings
            * TAB - History of recent activities - recent repair (reopen the repair)
            * TAB - Contact activity stacked bar chart - chart of arrears and profile of payments for year
            * TAB - Planned maintenance for the property
            * TAB - Cases tab
    * Caller and related to
        * Can hide information in cases of Dom Violence
        * Account information - multiple accounts shown as required
    * Contact management
        * List of contact history with the person
            * SMS - MScience - http://www.m-science.com - Account balances, etc.
        * Person records
            * GDPR - starred out NINO, others can be done as required
        * Asset details - Houses, estates, castles, power stations
            * Basics - inc GIS, OpenStreetMaps
            * Repairs history
            * Planned works
            * Performance - Repairs on time, types
            * Cases
            * Charges
            * Asset management
                * Cyclical maintenance items - Gas servicing
                * Planned maintenance - Kitchens
                * Other - 
                    * SAP rating
                    * White goods (gifted items)
                    * Stop tap locations
                    * Smart meter readings
                    * Flood risk scoring

* Rent accounting
    * Property based rents - void loss
        * Rent types
            * Frequencies - W, M, D, 6M, Q, Y
            * Configurable at tenancy start if wanted
        * Can see splits of charges - Basic, SC, Support.
        * Asset episodes - disposal and buyback management
    * Void assets
        * Decanted property
        * Void loss breakdown - can set up the void periods and auto calc void loss at each type
            * Some can be set to void loss exempt - WHQS, Decant, Managment decision
            * Low demand(?)
    * Financial accounts
        * Sub accounts - court, formers, repairs
            * Can be in statements
            * Cash reallocation - percentage, by amount, surplus amounts
    * Arrears process
        * Manual arrears
        * Suggested arrears - as at present, prompted actions
        * Automated arrears - one customer has a fully automated system
    * Account details
        * Personal Charges - Lifeline
    * Tenancy cancellation - can be undone even when confirmed **(Security lockdown!)**
        * Apportionment of charges
    * Rent uplift
        * Review system - by tenancy types/areas if required
            * Select what charges to uplift
            * By areas, rent review dates
            * %+£, % only
            * Can save progress, doesn't touch system until committed
            * Mistakes can be overwritten by running again with unchanged values
            * Multiple reviews at the same time (houses, garages, CS)
    * Proactive arrears
        * Profiled arrears
            * Configurable - high,med,low
                * Irregular payers

* Repairs
    * CRM Loggable - Different property, different dashboard
        * Log emergency repairs - a request is not a work order
            * Log inspection - then work order
            * 10% post inspections, inspect all for contractor - workflow configurable
            * Tasks - SORs - SMVs
                * Overridable priority
                * Can link to component in asset management
                    * HWC repairs > Replacement - Updates planned lifecycle
            * Tenant recharges - automatically goes to sub account
            * Shows history of recurrent repairs - can control by SOR
            * Trades and skills available to match contractors to jobs
            * Suggested appointments
                * Configurable using resources behind each contractor
            * Variations of SORs - reason required
                * Old lines not removed
            * Variations of contractors - re-raises work order automatically
    * Contractor portal
        * SORs
        * Completions
        * Variations

* Contractors system
    * List jobs by status
        * Allocated, Appointed, Complete, Cancelled, None of the above
    * **Discussion of the scheduling system requirements** 
    * Manual scheduling - shows the operatives that can complete the work
        * Highlights the time confirmed with the tenant
        * If the job is completed early, the screen changes to show the new free time

* Risk assessments
    * Categorise findings
        * Log repairs orders as required

* Planned maintenance
    * Smoothing of program
        * Configurable by age/condition/colour
    * Lifecycle Costing
        * By owning body (TC/MWH), area, street, asset
        * By year, month, quarter
        * Visual tool - can change the proposed spend by year - also split by area
            * Smoothing curve to show decreases in budget
            * Group elements together - kitchen & bathroom, roof elements
    * WHQS Acceptable failures reporting
        * As an attribute against the element
    * Save and apply plan for 0-30 years
        * Option to create work orders to send out in bulk, can drip feed xx at a time
        * Contract processing - for tenders, or direct award
            * With steps for meetings and agreements on payment terms
            * Apportion costs on property (with quantity balancing) or by asset data.
        * Can link a plan to a program of works

* Service charges
    * From spreadsheet
    * Apportioned in any flexible way
        * From spreadsheets, workflow of repairs/costs, percentage
        * Can set elements to not charge against property attributes.
        * Select assets by parent property
        * Propose and approval
    * Uplifts to apply the charges to the rent review, by rent period if set up.

* Reporting
    * Basic - show a list (Replace SMD lists)
    * Inter - a breakdown of arrears actions by officer
    * Advan - list of tenants that are over 70 - visual drag and drop
        * Properties with asbestos and tenants over 60