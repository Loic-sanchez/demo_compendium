 pantheria_data = function() {
  
   url <- "https://raw.githubusercontent.com/rdatatoolbox/datarepo/main/data/pantheria/PanTHERIA_1-0_WR05_Aug2008.txt"
   filename <- basename(url)
   path <- here::here("data", "pantheria")
   file_path <- here::here(path, filename)
   
   if(!file.exists(file_path)) {
     dir.create(path)
     utils::download.file(url, file_path, method = "auto")
     return(file_path)
   } else {print("File already exists")}
}

 wildlife_data1 = function() {
   
   url <- "https://raw.githubusercontent.com/rdatatoolbox/datarepo/main/data/wildfinder/wildfinder-ecoregions_list.csv"
   filename <- basename(url)
   path <- here::here("data", "wildfinder")
   file_path <- here::here(path, filename)
   
   if(!file.exists(file_path)) {
     dir.create(path)
     utils::download.file(url, file_path, method = "auto")
     return(file_path)
   } else {print("File already exists")}
 }
 
 wildlife_data2 = function() {
   
   url <- "https://raw.githubusercontent.com/rdatatoolbox/datarepo/main/data/wildfinder/wildfinder-ecoregions_species.csv"
   filename <- basename(url)
   path <- here::here("data", "wildfinder")
   file_path <- here::here(path, filename)
   
   if(!file.exists(file_path)) {
     dir.create(path)
     utils::download.file(url, file_path, method = "auto")
     return(file_path)
   } else {print("File already exists")}
 }
 
 wildlife_data3 = function() {
   
   url <- "https://raw.githubusercontent.com/rdatatoolbox/datarepo/main/data/wildfinder/wildfinder-mammals_list.csv"
   filename <- basename(url)
   path <- here::here("data", "wildfinder")
   file_path <- here::here(path, filename)
   
   if(!file.exists(file_path)) {
     dir.create(path)
     utils::download.file(url, file_path, method = "auto")
     return(file_path)
   } else {print("File already exists")}
 }
 