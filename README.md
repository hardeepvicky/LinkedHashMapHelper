# LinkedHashMapHelper
converting LinkedHashMap to json and vice versa

# use 

LinkedHashMap requestData = new LinkedHashMap();

LinkedHashMap auth = new LinkedHashMap();
auth.put("ServiceName", serviceName);
auth.put("Username", LoginUserEntity.username);
auth.put("Password", LoginUserEntity.password);
        
requestData.put("Authentication", auth);
        
JSONObject json = LinkedHashMapHelper.toJSONObject(requestData); // convert LinkedHashMap to json
