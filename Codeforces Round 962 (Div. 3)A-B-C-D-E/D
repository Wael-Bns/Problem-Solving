// Wael Benslimene DrStonee

#include<bits/stdc++.h>
#include <ext/pb_ds/assoc_container.hpp>

using namespace std;
using namespace __gnu_pbds;

template <class T>
using ordered_set = tree<T, null_type, less_equal<T>, rb_tree_tag, tree_order_statistics_node_update>;
#ifndef ONLINE_JUDGE
#include "debug.cpp"
#endif

const long long mod=1e9+7;
const long long MOD=998244353;
#define ll long long
#define endl '\n'
#define FAST ios::sync_with_stdio(false);cin.tie(0);cout.tie(0)
#define ff first
#define ss second
#define INF 1e18+5
#define yes cout<<"YES"<<endl
#define no cout<<"NO"<<endl
#define pb push_back
#define mp make_pair
#define all(x) (x).begin(),(x).end()
#define rall(x) (x).rbegin(),(x).rend()


ll binpow(ll a,ll b){ll res=1;while(b>0){if(b&1)res=(res*a);a=((a)*(a));b/=2;}return res;}
ll gcd(ll a,ll b){return b==0 ? a:gcd(b,a%b);}
ll lcm(ll a,ll b){return (a/gcd(a,b))*b;}
 

const int N=5e5+5;


void solve()
{
    int n,x;cin>>n>>x;
    ll ans=0;
    for(ll a=1;a<=n;a++)
    {
        for(ll b=1;b<=n/a;b++)
        {
            ans+=min(max(x-a-b,0ll),(n-a*b)/(a+b));
        }
    }   
    cout<<ans<<endl;
}   


int main()
{
    FAST;
    #ifndef ONLINE_JUDGE
    freopen("input.txt","r",stdin);
    freopen("output.txt","w",stdout);
    #endif
    int t=1;
    cin>>t;
    while(t--)
    {
        solve();
    }

    return 0;
}
