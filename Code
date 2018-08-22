sharedPreferences = getSharedPreferences("MyPref", Context.MODE_PRIVATE);
editor = sharedPreferences.edit();

// Read Data with Other Data Types

String stringValue = sharedPreferences.getString("stringKey","Data Not Found");
int intValue = sharedPreferences.getInt("intKey",0);
long longValue = sharedPreferences.getLong("longKey",0);
float floatValue = sharedPreferences.getFloat("floatKey",0f);
boolean boolValue = sharedPreferences.getBoolean("boolKey",false);

// Add Data with Other Data Types

editor.putString("stringKey","strawberry");
editor.putInt("intKey",12);
editor.putLong("longKey",123123);
editor.putFloat("floatKey",12f);
editor.putBoolean("boolKey",false);
editor.apply();
