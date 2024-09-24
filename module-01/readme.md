#Instruction 

rpk connect run 01-simple.yaml

rpk connect create -s kafka_franz/mapping/stdout 

rpk connect lint 02-lint.yaml

rpk connect test -h 03-convert.yaml