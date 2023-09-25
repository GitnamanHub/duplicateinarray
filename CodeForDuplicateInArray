int findDuplicate(vector<int> &arr) 
{
    int n = arr.size();
    int sumn = {0};
    int sumn1 = {0};
    for(int i=0;i<n;i++)
    {
        sumn+=arr.at(i);
    }	

    for(int i=1;i<n;i++)
    {
        sumn1+=i;
    }

    return sumn-sumn1;
}
