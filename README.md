In Vehicle Coupon Recommendation
This data checks whether a person will accept a coupon or not. This data was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios 
including the destination, current time, weather, passenger, etc., and then ask the person whether they will accept the coupon if they are the driver.
This is the field description,

destination: Specifying the destination they are going. No urgent place, Home, Work

passenger: Specifying the passengers in the car. Alone, Friend(s), Kid(s), Partner

weather: Sunny, Rainy, Snowy

temperature: 55, 80, 30 (Farenheit)

time: 2PM, 10AM, 6PM, 7AM, 10PM

coupon: Restaurant(<20), Coffee House, Carry out & Take away, Bar, Restaurant(20-$50)

expiration: 1d, 2h (the coupon expires in 1 day or in 2 hours)

gender: Female, Male

age: 21, 46, 26, 31, 41, 50plus, 36, below21

maritalStatus: Unmarried partner, Single, Married partner, Divorced, Widowed

has_child: 1,0

education: Specifying the education they have

occupation: Unemployed or specifying the occupation

Income: Specifying the range of income

Car: Specifying the name of the car

Bar: denoting the number of visit to the bar each month

CoffeeHouse: denoting the number of visit to the coffee house each month

CarryAway: specifying how many times you are getting take away food

RestaurantLessThan20: how many times do you go to a restaurant with an average expense per person of less than $20 every month?

Restaurant20To50: how many times do you go to a restaurant with average expense per person of 20− 50 every month?

toCoupon_GEQ5min: 0, 1, i.e. driving distance to the restaurant /bar is greater than 5 minutes

toCoupon_GEQ15min: 0, 1, i.e. driving distance to the restaurant /bar is greater than 15 minutes

toCoupon_GEQ25min: 0, 1, i.e. i.e. driving distance to the restaurant /bar is greater than 25 minutes

direction_same: 0,1, i.e. whether the restaurant/bar is in the same direction as your current destination

direction_opp: whether the restaurant/bar is in the opposite direction as your current destination

Y:1, 0 i.e. whether the coupon is accepted
