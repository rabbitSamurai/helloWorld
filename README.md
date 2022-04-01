# helloWorld
My first program 8D ---in python

--------------------------------------

print("Metric to USA feet converter")

unit = input("please write the size unity you want to convert TO: Metric or USA")

convert = input("please write the size unity you want to convert: Metric or USA")

if unit == "Metric" and convert == "USA":

    print("converting from metrics to USA...")
    metric = float(input("put the value in metrics:"))
    calculation = metric * 3.2808
    print(metric, "meters is ", calculation, "ft")

if unit == "USA" and convert == "Metric":

    print("converting from USA to metrics..")
    USA = float(input("put the value in feet:"))
    calculation = USA * 0.305
    print(USA, "ft is", calculation, "in meters.")

