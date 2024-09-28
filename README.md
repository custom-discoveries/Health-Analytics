# Health-Analytics
The Health-Analytics database application shows the interactions between providers refering patents to other providers.
## Install and Run
### Install
To install this TigerGraph demo, clone this repository at a terminal command prompt: 
- \>git clone https://github.com/custom-discoveries/Health-Analytics.git
### Run Cheetah in Cloned Directory:
-  cd Health-Analytics
-  Health-Analytics\> Cheetah [^1]
    - Select -b option to load both the schema & data
    - Select -q (sub option -b) to Define and Install the queries
[^1]: See Cheetah [README.md](https://github.com/custom-discoveries/Cheetah/blob/main/README.md) for installation and setup of Cheetah
### In TigerGraph GraphStudio:
Run the query scripts in TigerGraph GraphStudio Write Queries:
1. referral_subquery[1].gsql
2. _delete_referral_edges.gsql
3. algo_louvain.gsql
4. ex_main_query.gsql
5. get_claims_of_provider.gsql
6. get_common_patients.gsql
7. get_joint_providers.gsql
8. get_k_hop_neighbors.gsql
9. get_patients_of_provider.gsql
10. get_referral_community.gsql
11. tg_pagerank.gsql
