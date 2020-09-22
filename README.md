# Amazing-python
Basic python tutorials with code, sufficient to start ML & some cool hacks that makes a python superb among all other languages.

def find_object_methods_and_variables(obj):
    object_methods=[]
    object_variables=[]
    for entity in dir(model_bp1):
        if callable(getattr(model_bp1, entity)):
            object_methods.append(entity)
        else:
            object_variables.append(entity)
    
    return object_methods, object_variables
