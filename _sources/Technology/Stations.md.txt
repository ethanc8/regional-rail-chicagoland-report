# Stations

> Infrastructure modifications to enhance accessibility and speed the boarding process are essential to fulfilling this vision and improving service for all riders. The wide doors on modern trains cannot serve low platforms, thus requiring high level platforms at all stations. Most MBTA stations do not have such platforms and because of a recent rules change, any modification to a current station requires a full-length, high-level platform. Based on several recent projects procured by the MBTA, an 800-foot, high-level platform costs between \$1.5 and \$2 million, with additional spending for associated costs. These costs vary: at stations where vertical circulation is already in place (along the Providence Line, for instance) there would be minimal costs beyond the platforms themselves. In these cases, the total cost to build the high level station would be in the \$4 to \$5 million range. At other stations, ramps and elevators would be required, increasing costs while providing full accessibility for passengers. In still other locations, freight railroad clearances require track and platform modifications, resulting in higher costs. A rough estimate would put the average cost of high-level platforms at stations that do not currently have them in the \$8 to \$10 million range. The cost of designing and building high-level platforms can be contained by utilizing standardized designs for these platforms. Each station does not require an expensive bespoke design. Use of standard design specifications (which may require modest modification in appropriate circumstances) and creative use of materials can make a meaningful difference in keeping the cost of this important equity and service improvement in reasonable and affordable territory.
> -- [*Regional Rail for Metropolitan Boston*](https://transitmatters.org/regional-rail-doc#:~:text=High-Level-,platforms,-Metro%20North%20enables), TransitMatters


## Needed design elements

### High-level boarding

% TODO

### Fare validators or faregates

### Platform length

:::{figure-md}
![A table showing the minimum platform length for Metra stations](img/minimum-platform-length.png)

The minimum platform length for Metra stations, according to the [2007 *Metra Commuter Rail Station Guidelines and Standards*](https://assets.metra.com/s3fs-public/inline-files/station_guidelines_standards0807.pdf).
:::

We assume for these purposes that all new stations should be 720 ft (219.5 m) if there is sufficient space.

## Cost table

These are based on the example low-cost station designs included below. Simple headhouses and shelters are included in the costs.

| Type                                              | Cost |
| ------------------------------------------------- | ---- |
| Embankment center platform + vertical circulation | $12M |
| Open-cut center platform + vertical circulation   | $10M |
| At-grade center platform                          | $    |
| At-grade, two side platforms                      | $5M  |

## Example low-cost station designs

### Standard South Shore Line station

% TODO

### Standard Metra Electric embankment station

% TODO: Add pictures

79th Street/Chatham, 87th St/Woodruff, and 103rd St/Rosemoor are currently (2025) being reconstructed for a total of \$33.9 million USD[^me339cost], which comes out to \$11.3 million USD per station on average. This consisted of removing an existing center platform only accessible via stairwell, and installing a new platform with elevator access, shelter, maps, digital displays, and automated announcements.

% TODO: Harvey and Sibley

[^me339cost]: https://metra.com/newsroom/metra-to-reopen-103rd-strosemoor-station-close-95th-stchicago-state-on-march-3-0

### Open-cut station (11th/Museum Campus design)

% TODO: Add picture of 11th/Museum Campus

A new station with two island platforms was built in 2009 to replace the dilapidated Roosevelt station (a remnant of the IC's former Central Station). It was built by Blinderman at a cost of \$10.4 million USD[^museumcampus] (equivalent to \$16.7 million USD in 2025[^museumcampusenrcci], or $8.4 million USD per platform).

[^museumcampus]: <https://blinderman.com/projects/roosevelt-road-metra-train-station>

[^museumcampusenrcci]: We use the [ENR CCI](CostIndices#enr-cci) values of 8570 for 2009 and 13760.31 for late 2024-mid 2025: $
  10.4 \text{ million USD} * \frac{13760.31}{8570} \approx 16.7 \text{ million USD}$.

### At-grade island platform station (South Chicago rebuildings)

% TODO: Find these examples

### At-grade side platform station (SEPTA 9th Street design)

% TODO: Find some other examples

:::{figure-md}
![An image of the SEPTA 9th Street station](img/SEPTA_9th_Street_station,_January_2016.jpg)

The SEPTA 9th Street station shows that low-cost stations do not have to look utilitiarian or lack useful amenities.

<small>Montgomery County Planning Commision, CC-BY-SA 2.0, [edited by Wikipedia editor User:Pi1415926535](https://commons.wikimedia.org/wiki/File:SEPTA_9th_Street_station,_January_2016.jpg)</small>
:::

SEPTA's [9th Street station](https://en.wikipedia.org/wiki/9th_Street_station_(SEPTA)) contains:
* a 256 ft (78 m) long high-level side platform
* a shelter, stairwell, and ramp to access the platform
* a parking lot and bike rack

The station was built for around \$3.8 million USD in 2015 (equivalent to \$5.2 million USD in 2025 [^3.8musd]). It took around 10 months to design and approve the station, and around 8 months to construct the station.

A pessimistic estimate for the cost of building a station with two side platforms 720 ft long, shelters, and a parking lot, in an unconstrained location, where the customers cross the tracks at an existing grade crossing to switch between platforms, is **\$29.3 million USD**. This is a *high overestimate*, as this counts various costs that don't scale with platform length, such as the parking lot or bike rack, multiple times.

$$
5.2 \text{ million USD} * \frac{2 * 720 \text{ ft}}{256 \text{ ft}} \approx 29.3 \text{ million USD}
$$

[^3.8musd]: We use the [ENR CCI](CostIndices#enr-cci) values of 10035 for 2015 and 13760.31 for late 2024-mid 2025: $
  3.8 \text{ million USD} * \frac{13760.31}{10035} \approx 5.2 \text{ million USD}$.


