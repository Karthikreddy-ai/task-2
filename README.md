cities = ["New York", "Tokyo", "Paris", "Sydney", "Cairo"]
print("Initial list of cities:", cities)
middle_index = len(cities) // 2
print("City at the middle index:", cities[middle_index])
subset_cities = cities[:3]
print("First 3 cities:", subset_cities)
cities.sort()
print("Cities sorted in ascending order:", cities)
cities.append("Berlin")
print("List after appending a new city:", cities)
cities.pop(0)
print("List after removing the first city:", cities)
def get_list_length(city_list):
    return len(city_list)
list_length = get_list_length(cities)
print("Length of the list:", list_length)
