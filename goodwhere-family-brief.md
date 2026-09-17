# GOODWHERE product family

Six proposed product forms for different customers, routines and power needs. Original industrial-design concepts, not validated specifications.

## The recommendation
Build one coherent brand with six product briefs. Stage the launches: One + Max first, Pocket + Trail as dedicated next programs, Drive as a partner-led extension, and Dot as an optional entry product. Product availability, integrations and pricing are not established.

## Goodwhere Dot
- **Buyer:** Everyday households, students and forgetful commuters
- **Use:** Keys, a backpack zipper or an everyday carry pouch
- **Design target:** 32 × 28 × 8 mm
- **Architecture:** Bluetooth finder
- **Job:** Ring a nearby item and help locate it through the supported finding experience.
- **Power:** Serviceable coin-cell concept. Low-power finding rather than frequent GPS reporting.
- **Tradeoff:** No independent cellular updates or continuous route history. Any crowd-finding network requires approval and may use its own native app.
- **Commercial role:** Purchase-led; no assumed $200 annual subscription
- **Proposed features:** Nearby ring, Last-seen context, Simple attachment
- **Creative opening:** The little things. Found.

## Goodwhere Pocket
- **Buyer:** Commuters, creators and frequent ground travellers
- **Use:** A work bag, camera bag or valuable carry gear
- **Design target:** 54 × 34 × 14 mm
- **Architecture:** Rechargeable cellular GPS
- **Job:** Get independent location updates for a bag that matters, plus movement and boundary alerts.
- **Power:** Compact rechargeable battery. Design for an easy, regular charging habit and selectable update modes.
- **Tradeoff:** Smaller battery volume means a tighter runtime budget. Air-travel use would need separate airline, battery and radio compliance work.
- **Commercial role:** Connect plan; price and reporting allowance to validate
- **Proposed features:** Location check, Movement alerts, Bag-safe zones
- **Creative opening:** Carry on. Check in.

## Goodwhere Trail
- **Buyer:** Dog owners who walk, travel and spend time outdoors
- **Use:** A secure, low-profile fit on a dog's collar
- **Design target:** 52 × 32 × 17 mm
- **Architecture:** Dedicated pet cellular GPS
- **Job:** Support escape alerts, a location session when needed and a record of walks.
- **Power:** Rechargeable with home power-saving modes as a design goal. Frequent location sessions shorten runtime.
- **Tradeoff:** Fit, weight, collar retention, bite resistance and ingress require dedicated testing. Suitable dog sizes are not yet established.
- **Commercial role:** Pet-focused Connect plan; validate willingness to pay
- **Proposed features:** Escape alerts, Find session, Walk history
- **Creative opening:** For the one who follows you everywhere.

## Goodwhere One
- **Buyer:** Cherished-car, camper and leisure-gear owners
- **Use:** An owned vehicle, camper or valuable equipment
- **Design target:** 76 × 46 × 19 mm
- **Architecture:** Portable cellular GPS
- **Job:** Keep an eye on a valued asset through location, movement alerts, boundaries and route history.
- **Power:** A balanced rechargeable format. More battery volume than Pocket; charging cradle and removable mounts proposed.
- **Tradeoff:** Mounting position affects radio performance. It still needs coverage, battery maintenance and validated environmental limits.
- **Commercial role:** Connect plan; existing $200 annual case is a hypothesis
- **Proposed features:** Movement alerts, Safe zones, Route history
- **Creative opening:** For everything you'd go back for.

## Goodwhere Max
- **Buyer:** Trailer owners, tradespeople and equipment operators
- **Use:** A stored camper, work trailer or equipment locker
- **Design target:** 108 × 68 × 30 mm
- **Architecture:** Large-battery cellular GPS
- **Job:** Check on an asset between visits and get movement alerts without a pocket-sized battery constraint.
- **Power:** Largest proposed battery envelope. Storage and active modes balance check-in frequency against runtime.
- **Tradeoff:** Bigger and heavier. No months-long live-tracking promise; antenna clearance, mount retention and exposure testing remain essential.
- **Commercial role:** Asset Connect plan; cadence-sensitive economics
- **Proposed features:** Storage check-ins, Movement alerts, Shared asset access
- **Creative opening:** Big plans. Longer stays.

## Goodwhere Drive
- **Buyer:** Daily drivers, family-car owners and owner-operated couriers
- **Use:** A compatible vehicle with an accessible OBD-II port
- **Design target:** 48 × 42 × 25 mm + connector
- **Architecture:** Vehicle-powered cellular GPS
- **Job:** Maintain a trip record and vehicle visibility with power from the vehicle.
- **Power:** Vehicle supply rather than a routine charging chore. Parked-current draw and low-voltage protection must be engineered.
- **Tradeoff:** Vehicle compatibility and port clearance vary. Unplugging or losing vehicle power can stop reporting; backup behavior is not yet specified.
- **Commercial role:** Drive Connect plan; per active vehicle
- **Proposed features:** Trip history, Arrival alerts, Device power status
- **Creative opening:** Plug in. Get on with it.

## The common system
The cellular range aims for one account, clear location and last-update status, device health, useful movement/boundary alerts, route history where appropriate, invitations and permissions. Preset modes should express real reporting and battery tradeoffs. Accessories should solve attachment and charging jobs. A unified billing experience does not imply that all devices share identical firmware or radio hardware.
Dot is the exception: nearby Bluetooth finding can work differently from GPS. Any crowd-finding network requires approval and may require a native platform app; access to that network’s location data from Goodwhere cannot be assumed.

## Bundles by customer
- Daily set: Pocket + Dot for work bag and keys.
- Weekend set: One + Trail for camper and dog.
- Working set: Drive + Max for powered van and unpowered trailer.

## Economics and validation
Do not multiply all units by $200. Sum each cellular SKU’s active paying devices × realized plan revenue. Dot is purchase-led. Model activation, acquisition, returns, support, cellular data and retention by SKU and customer group. No margins, prices or runtime figures have been validated.
Freeze batteries, antennas and boards before exterior CAD. Validate product-specific mounting, charging, ingress, drops, temperature and reporting behavior. Trail needs dedicated fit, retention and animal-use testing; Drive needs vehicle compatibility, quiescent-current and power-loss testing. Compact Pocket needs a believable recharge routine. Max needs measured standby and active-mode behavior. Human care/SOS and air-travel claims require separate product work.

## Evidence informing the architecture
- [Apple AirTag 2 technical specifications](https://support.apple.com/en-ae/126203): Bluetooth/UWB and coin-cell example, not a Goodwhere implementation commitment.
- [Tractive battery guidance](https://help.tractive.com/hc/en-us/articles/360000483620-How-to-boost-battery-life): reporting frequency, weak coverage and power-saving behavior affect runtime.
- [Bouncie FAQ](https://help.bouncie.com/en/articles/1738280-bouncie-faqs): OBD power, parked mode and compatibility considerations.

GOODWHERE remains a working brand name pending formal clearance. All family names and designs are proposals.
