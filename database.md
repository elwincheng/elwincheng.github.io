If you are using HDD, use LSM Tree storage engine. It makes writes sequential. This is more friendly for the HDD. The HDD will wear out at a slower pace as the physical rotors will have to do less work so there will be less mechanical failures. Decrease the possibility of drive failures. Saves money from always replacing failed drives. 

Data Lake: A fast cheap storage for messy unstructered data

Data warehouse: Structured data storage for analytical workloads.

If you have analytical workload, use Columnar Store/Data warehouse like AWS Redshift.

If you have transactional SQL / relational workload, use AWS Aurora.
