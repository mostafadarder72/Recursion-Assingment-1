void permute( const string &str )
{
    int low = 0;

    int high = str.length();

    permute(str, low, high);

}
permute(str, 0, str.length());

Explanation:

void permute( const string &str, int low, int high)  

{
    string str1 = str;

     if ( low == high )
    {

           for (int i = 0; i <= high; ++i)

                 cout << str1[i];
    }  

     else
    {

           for (int i=low; i<high; ++i)
        {
             

                 string temp = str1;
             

                 swap( str1[i], str1[low] );

                 permute( str1, low + 1, high );
             

                 swap( str1[i], str1[low] );
               
        }  
    }
}

//*******************************************************
int main()
{

    string str;

    cout << "Enter a string : ";

    cin >> str;

    permute(str);
}
