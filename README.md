# LinkedHashMapHelper
converting LinkedHashMap to json and vice versa

# How to Use 

LinkedHashMap requestData = new LinkedHashMap();

LinkedHashMap auth = new LinkedHashMap();

auth.put("ServiceName", "Login");

auth.put("Username", "user");

auth.put("Password", "123");
        
requestData.put("Authentication", auth);
        
JSONObject json = LinkedHashMapHelper.toJSONObject(requestData); 
