namespace Mianaqu;

final class Profile
{
    public function __construct(
        public readonly string $name      = 'Michael Andrea Aquino',
        public readonly string $role      = 'Web Developer',
        public readonly array  $stack     = ['PHP', 'Laravel', 'Filament', 'Tailwind CSS', 'Vite'],
    ) {}

    public function contact(): array
    {
        return [
            'email'  => 'michaelandrea060@gmail.com',
            'github' => 'https://github.com/Mianaqu-F',
            'instagram' => 'https://instagram.com/mianaqu',
        ];
    }
}

$me = new Profile();
