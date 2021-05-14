!!IMPORTANT!!

In order to use this in Unity, you will need to make a wrapper class for the dictionary you wish to display. This can be done by doing the following:

public class NewDictionary : UDictionary<keyType, valueType>
{
	// don't worry about putting anything here...leave it blank
}

After this, the dictionary should display in the inspector!