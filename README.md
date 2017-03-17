# mmqgis-fork-v2
mmqgis based address geocoding with features added
(Works with small number of addresses. Point freaures always created, but fails to exit properly after completion with large number of addresses.)

-			Linear interpolation on curved streets
-			Allowance for (numeric) post code alterations
-			Allowance for both street sides having same parity
-			Allowance for mixed parity
-			Allowance for house number /a - /g (with floating number value)
-			Reduced setback on shorter streets
-			Corner setback based on relative (assumed) parcel width
-			Logging reference centerline source feature ID
-			Quality measure added for street name / post code / house nr. match
-			Original len(addresses) <> address_count bug fixed

(Only modified scripts are loaded.)
