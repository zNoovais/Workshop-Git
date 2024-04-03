# Workshop-Git

typedef enum movimento {Norte, Oeste, Sul, Este} Movimento;

typedef struct posicao
{
    int x, y;
} Posicao;




Posicao caminho(Posicao inicial, Movimento mov[], int N)
{
    int i; 
    for( i = 0; i < N; i++)
    {
        if(mov[i] == Norte)
        {
            inicial.y++;
        }
        else if(mov[i] == Oeste)
        {
            inicial.x--;
        }
        else if(mov[i] == Sul)
        {
            inicial.y--;
        }
        else if(mov[i] == Este)
        {
            inicial.x++;
        }
    }
    return inicial;
}


Repositório para o workshop de git
No dia 3 de Abril
