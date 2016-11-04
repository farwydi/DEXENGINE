# DEXENGINE

>Open Source graphic games engine

### Syntax

```cpp
class DEX_EXPORT DEXClassName : public DEXClassParent
{
    public:
        DEXClassName(const unsigned int inPar, void* inPointer, int& outVar);
        ~DEXClassName()

        void* getCustomFunction(bool inUseFunction = true);
        bool getVarNam() { return bVarName; }
        
    private:
        bool			bVarName;
	    DEXSomeClass*	pCustomClassInfo;
	};

DEXClassName::DEXClassName(const unsigned int inPar, void* inPointer, int& outVar)
    : DEXClassParent(inPointer), bVarName(false), pCustomClassInfo(nullptr)
{
    if (auto pSomeClass = dynamic_cast<DEXSomeClass*>(inPointer))
    {
        // Some code
    }

    for (auto localName : inNames)
    {
    	// Some code
    }

    for (unsigned int localN; localN < 99; localN++)
    {
    	// Some code
    }

    while (localVarName)
    {
    	// Some code
    }

    {
    	// Some code
    }
    while ((localVarName1 > 5) && ((localVarName2 == localVarName3) || localVarName0))
}

DEXClassName::~DEXClassName()
{
    // Some code
}


void* DEXClassName::getCustomFunction(bool inUseFunction)
{
	// Some code
}
```