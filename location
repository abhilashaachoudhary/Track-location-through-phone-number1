import phonenumbers

from number import number

from phonenumbers import geocoder

victimNumber = phonenumbers.parse(number)

yourLocation = geocoder.description_for_number(victimNumber, "en")
print(yourLocation)

# get service provider

from phonenumbers import carrier

service_provider = phonenumbers.parse(number)
print(carrier.name_for_number(service_provider, "en"))
