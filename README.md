# bfs-template
#adding a edge
vector<vector<int> >edge;
edge.assign(n,vector<int>());
edge[a].push_back[b];
vector<bool>v;
v.assign(n,false)
#bfs(int u)
{
  queue<int> q;
  q.push[u]
  v[u]=true;
  while(!q.empty())
  {
      int f=q.front();
      q.pop()
      vector<int>::iterator i;
      for(*i=edge[f].begin();*i=edge[f].end();i++)
      {
        if(!v[*i])
        {
          q.push[*i];
          v[*i]=true;
        }
      }
  }
}
