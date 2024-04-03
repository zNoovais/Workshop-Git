# Workshop-Git
Repositório para o workshop de Git/Github!

apresentado no dia 03/04/2023 dado inicio as 14:00.


















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





















