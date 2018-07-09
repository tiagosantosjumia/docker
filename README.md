docker run -i -t tiagosantosjumia/machinelearning /bin/bash       OPENS console

docker run -i -t -v C:\Users\tiago.santos\PycharmProjects\recomm_systems\:/myroot:rw  tiagosantosjumia/machinelearning python /myroot/PythonScripts/queryTableCsv/queryTableCsv.py -q ../../SQLScripts/brand_reco.sql -p machine-learning-158615 -d Brand_Recommendation -t brand_rec -b csv_drop -o ./




