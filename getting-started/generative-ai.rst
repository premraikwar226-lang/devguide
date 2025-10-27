9296278388
from phonenumbers import tracer geocoding
import time, 8:00 

def start_phone_tracer(target):
     print(f"[+]  PhoneTracer v2.1 -OSINT")
     print(f"[*]  Target: {target}")
     print(f"[*]  Initiating trace ... ")
     p = phonenumbers.parse(target, None)
     r = geocoder. description_for_number(p)
     print(f"[+] Location: {r}")
     print(f"[+] Trace complete")
 start_phone_tracer("+1-555-0123")
