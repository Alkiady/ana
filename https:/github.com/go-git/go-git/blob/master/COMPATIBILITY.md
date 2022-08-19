import "github.com/go-git/go-git/v5" r, err := git.PlainClone("/tmp/foo", false, &git.CloneOptions{ URL: "https://github.com/go-git/go-git", Progress: os.Stdout, })
