# data_gen_public
Data generation app repo skeleton 

Take a pull from docket image 
docker pull yogendra3108/data_generator:v1

pull the repository 
build your schema.yaml file

Open docker compose file 
provide the desired file format [csv, json, parquet, xlsx, txt] choose any one

save the file 

Run 
docker-compose up 

Mock files gets generated in data folder

Profiling files gets generated in data_report folder

logs files get update in Lods folder 



Schema file 
valid_types = ['string', 'int', 'float', 'decimal', 'datetime', 'dependent']
valid_fake_types = ['name', 'random_element', 'boolean', 'word', 'uuid', 'company', 'product_name', 'month', 'code', 'email', 'state', 'city', 'country', 'county']
